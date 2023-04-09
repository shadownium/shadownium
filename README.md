```java

import galaxy.earth.shadow;
public class Shadow {

    static void languages(){
        String languages = {"Java","TypeScript","Python"};
        for(byte control = 0; control <= languages.length; control++){
            System.out.println("I code in :" + languages[0]);
        }
    }
    static void frameworks(){
        String frameworks = {"Next.JS","Arduino","Node.JS","Pytorch","Android"};
        for(byte control = 0; control <= frameworks.length; control++){
            System.out.println("I write in " + frameworks[0] + " framework");
        }
    }
    static void about(){
        String goals = {"Open Source", "Wolf Squad", "Robotics"};
        for(byte control = 0; control <= goals.length; control++){
            System.out.println("Writing code for" + goals[0]);
        }
    }
    static void main(String args[]){
       Shadow dark = new Shadow();
       dark.languages();
       dark.frameworks();
       dark.about();
    }
}
```
![Top Langs](https://statx.vercel.app/api/top-langs/?username=5H4X)
