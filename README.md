## 🧠 TryCatchAllDev.java

Porque todo dev tem seus dias de exceção...

```java
public class TryCatchAllDev {
    public static void main(String[] args) {
        try {
            System.out.println("Tentando ser uma dev equilibrada...");
            throw new Exception("A vida não colaborou");
        } catch (Exception e) {
            System.out.println("Refatorando o caos. Commitando com medo. Vivendo com ironia.");
        }
    }
}
