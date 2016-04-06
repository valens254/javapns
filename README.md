#Apple Push Notification Service Provider for Java

#JavaPNS 2.2

JavaPNS is a Java library to send notifications through the Apple Push Notification Service
Welcome to the JavaPNS project, home of the most user-friendly, powerful and fine-tuned Java library for APNS! This fully-featured Java library allows developers to push notifications to iOS devices **(iPhone, iPod, iPad, etc.)** through the Apple Push Notification Service using a simple yet powerful set of tools. First-time users will find the library to be extremely easy to use (**start with a single line of code!**), while advanced users will benefit from the library's flexible design and scalability features.

##Capabilities
* Start sending notifications using a single line of code
* Get started quickly with smart default settings
* Easily switch between Apple's sandbox or production services
* Use predefined simple notifications, or create custom and/or complex payloads
* Benefit from the enhanced notification format
* Send thousands of notifications using the built-in multithreaded transmission engine
* Examine push notification results immediately and accurately
* Query the Feedback Service with a single line of code to find inactive devices
* Auto-resend notifications ignored by Apple servers after an error
* Push notifications to Apple's Newsstand application with one line of code
* Setup connection pools (queues) in no time
* Use bundled command-line tools to test push notification and feedback
* Rely on the library's strong error and exception management
* Get started quickly thanks to the built-in safeguards against common mistakes
* Build upon JavaPNS's developer-friendly API to extend its functionalities
* Learn everything about the library through its complete and up-to-date javadoc
* **and much more!**

##Get started
1. Read the documentation
2. Meet the requirements
3. Push notifications

##Usage
The simplest way of pushing notifications with JavaPNS is to use the javapns.Push class:


```java
import javapns.Push;

public class PushTest {
 
    public static void main(String[] args) {
        Push.alert("Hello World!", "keystore.p12", "keystore_password", false, "Your token");
    }
}
```

Licensed under the GNU LGPL license v3.0 .

Automatically exported from [code.google.com](https://code.google.com/p/javapns)
