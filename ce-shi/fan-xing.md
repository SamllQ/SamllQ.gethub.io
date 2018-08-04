泛型类定义：一个泛型类是指的是，顶一个个嘞，这个类中的某些字段的类型是不确定的，这些类型可以在类构造的时候确定下来

```
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace 泛型类
{
    class Program
    {
        static void Main(string[] args)
        {
            var ak = new ClassA<string>("8888", "77777");
            Console.WriteLine(ak.GetSum());
            Console.ReadKey();
        }
    }

    class ClassA<T>  //泛型类定义的时候需要在类名后面加<T:代表类型>
    {
        /// <summary>
        /// T类型的变量 （类型不知，需要在构造函数里面给T指定类型）
        /// </summary>
        public T num;
        /// <summary>
        /// T类型的变量（类型不知，需要在构造函数里面给T指定类型）
        /// </summary>
        public T num1;
        /// <summary>
        /// 泛型类的构造函数
        /// </summary>
        /// <param name="a"></param>
        /// <param name="b"></param>
        public ClassA(T a, T b)
        {
            this.num = a;
            this.num1 = b;
        }
        public string GetSum()  
        {
            return num +""+ num1;
        }
    }
}

泛型方法：定义泛型方法就是定义一个方法，这个方法的参数的类型可以是不确定的，当调用这个方法的时候再去确定方法的参数的类型

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace 泛型类
{
    class Program
    {
        public static string GetAdd<T>(T a,T b)
        {
            return a +""+ b;
        }
        static void Main(string[] args)
        {
            Console.WriteLine(GetAdd(55,88));
            Console.WriteLine(GetAdd("5", "ss"));
            Console.WriteLine(GetAdd("5655565","88dsd"));
            Console.ReadKey();
        }
    }
}
```

\`\`\`

