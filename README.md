<img width="274" height="110" alt="image" src="https://github.com/user-attachments/assets/bab7e3c9-83e0-4f71-b067-4a792be06f55" />
<img width="311" height="78" alt="image" src="https://github.com/user-attachments/assets/fd23b1a9-04f9-495b-b3b7-4dbcb11e2cb2" />
            string[] fruits = { "banana", "apple", "orange", "pear", "grape", "pineapple" };
            Console.WriteLine("Enter a fruit to search for:");
            string userFruit = Console.ReadLine();
            bool found = false;

            for (int i = 0; i < fruits.Length; i++)
            {
                if (fruits[i] == userFruit)
                {

                    found = true;
                    break;
                }
            }

            Console.WriteLine(found);

