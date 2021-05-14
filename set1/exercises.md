1. Givet ett program med två variabler:

        let a = random(10);
        let b = random(10);
        print(a,b);

    Utöka programmet så att variablerna `a` och `b` byter värde med varandra
    
    <details>
        <summary> Lösning </summary>

    Vi måste introducera en temporär variabel som vi använder till att mellanlagra värdet på en av de andra variablerna.
    
        let t = a;
        a = b;
        b = t;
    
    </details>

    <br>
    
    
1. Skapa en moln liknande molnet nedan genom att placera ut tre cirklar. Punkerna i bilden illustrerar ciklarnas mittpunkter.

	![image](./moln.png)
