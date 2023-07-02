# Pavel Chepikov
![logo](https://cutewallpaper.org/21/pharah-phone-wallpaper/Low-poly-Pharah-4k-wallpapers.png)

## Student BSUIR

## Contact informateion
**E-mail:** pavelchepikov07@gmail.com
**Discord(rsschool):** Paul Ch___v
  
## Briefly About Myself:
As a student at the university, I tried languages ​​such as C #, C ++, Python, JS and others as laboratory work, but at the moment I would like to develop either in the direction of game development or front-end development, as I see this as a way to combine technical skills and creativity. In my free time I study CG-Art and Photoshop.  
  
## Skills and Proficiency:
* HTML, CSS, JavaScript, React - Basics
* VS Code, IntelliJ IDEA
* MySQL, OracleDatabase
* Adobe Photoshop
  
## Code example:
  **Part of the university assignment**: *Given a string consisting of lowercase English letters. Replace all letters in it after the vowels with the following alphabetically (z is replaced by a).*
  ```
    using System;
    using System.Text;

    namespace LR2._3
    {
        class Program
        {
            static void Main(string[] args)
            {
                Random random = new Random();
                StringBuilder text = new StringBuilder("ajxyieualtirctbayultwuyrabyzikyudfilctayrxlnwiafhusd,tcyilyxiaofhnguailtyux.nHz.xtu,zgbhjcdtyara;io;zuitryicwtau");
                StringBuilder vowels = new StringBuilder("eyuioa ");

                Console.WriteLine(text);
                for (int i = 0; i < text.Length; i++)
                {
                    for (int j = 0; j < vowels.Length; j++)
                    {
                        if(text[i]==vowels[j])
                        {
                            if (text[i + 1] == 'z')
                            {
                                text[i + 1] = 'a';
                                continue;
                            }
                            text[i+1] = Convert.ToChar(Convert.ToInt32(text[i+1])+1);
                        }
                    }
                }
                Console.WriteLine(text);
                Console.ReadLine();
            }
        }
    }
  ```

## Education:
* BSUIR - System Programmer Engineer - Higher education (in progress)
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
  
## Languages:
* English - Basic
* Russian - Native
* Belarusian - Native

