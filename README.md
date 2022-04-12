# public-access-modifier


namespace ConsoleApp10
{
    class car
    {
        public string modol="mustang";
        public int year=1989;
        public string color="red";
        static void Main(string[] args)
        {
            car c = new car();
            Console.WriteLine(c.modol);
            Console.WriteLine(c.year);
            Console.WriteLine(c.color);
            Console.ReadLine();
        }
    }
}
