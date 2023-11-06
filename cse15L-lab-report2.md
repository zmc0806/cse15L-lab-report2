Part1
code

![image](https://raw.githubusercontent.com/zmc0806/cse15L-lab-report2/main/code.jpeg)

In the `Handler` class, I implemented a method called `handleRequest` that is responsible for handling URL queries. This method takes a single parameter: the URL of the website to be queried. The URL should include specific details, such as the website's path, the key for querying, and the messages that need to be retrieved.

For updating the website with new messages, the method modifies the URL by appending `"/add-message?s="` to the end of the URL string. The `Handler` class has an `ArrayList<String>` field named `messages` that stores all the messages. Each time a new message is submitted using the query `"/add-message?s="`, this message is added to the `ArrayList`.

For example, when I submit a query using `"/add-message?s=Hello"`, the string "Hello" becomes the first message in the `messages` ArrayList, and as a result, it is displayed on the website.

Regarding the class field `num`, it is indeed a relevant field in the `Handler` class. This integer field tracks the number of messages that have been added. With each `"/add-message"` request, the `num` field is incremented by one, reflecting the total count of messages stored in the `messages` ArrayList. After processing a message addition, `num` is updated to ensure that it always represents the current number of messages held in the list.

![image](https://raw.githubusercontent.com/zmc0806/cse15L-lab-report2/main/Hello.jpeg)

Second I use /add-message?s=How are you,How are you become second message in Webpage.

![image](https://raw.githubusercontent.com/zmc0806/cse15L-lab-report2/main/howareyou.jpeg)

I also try add my name in webpage,it's become third message

![image](https://raw.githubusercontent.com/zmc0806/cse15L-lab-report2/main/myname.jpeg)


Part2

![image](https://raw.githubusercontent.com/zmc0806/cse15L-lab-report2/main/1.jpeg)

![image](https://raw.githubusercontent.com/zmc0806/cse15L-lab-report2/main/2.jpeg)

![image](https://raw.githubusercontent.com/zmc0806/cse15L-lab-report2/main/3.jpeg)

Part3

During weeks 2 and 3, my educational journey was significantly enriched as I acquired a multitude of new skills and insights. Among these, I mastered the technique of securely logging into a remote server via SSH, a process that not only enhanced my system administration capabilities but also deepened my comprehension of network security. 

In essence, these novel learning experiences have not only embellished my skill set but have also kindled a fervent passion for deeper exploration within the IT realm.
