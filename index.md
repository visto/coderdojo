## CodeDojo Berlin - Minecraft Einführung



Code: 
git clone https://github.com/ReneHollander/empty-spigot-plugin.git


IDEA:
Download https://www.jetbrains.com/idea/download/ and install
Add Java SKD

Configure>> Project Defaults >> Project Structure >> Project >> New... >> /Library/Java/JavaVirtualMachines/jdk1.8.0_xxx.jdk/Contents/Home


Linux/OSX: 

Open Terminal
Navigate into cloned repository
Execute:
./gradlew idea
./gradlew buildSpigot
./gradlew build

Open the project in IntelliJ by opening the created .ipr file. Otherwise the run configurations will not be in place for you!






