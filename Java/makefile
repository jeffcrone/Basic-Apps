build: HelloWorldMain.java  com/jeffcrone/HelloWorldClass.java
	javac HelloWorldMain.java  com/jeffcrone/HelloWorldClass.java
	jar cfe HelloWorld.jar HelloWorldMain HelloWorldMain.class com/jeffcrone/HelloWorldClass.class

clean:
	rm -f HelloWorld.jar *.class com/jeffcrone/*.class

run:
	java -jar HelloWorld.jar
