## Executive Summary ##

In Unit 6, we explore protocols that support communications on the Internet, Internet architecture, and Internet Security. We also look at various internet programming methodologies, and practice creating a website using HTML and CSS. Finally, the components of a URL are explained and we take a look at both relative and absolute file paths.

### Internet Architecture ###

#### Internet Protocol ####

Internet Protocol **(IP)** addresses are the unique numbers assigned to every computer or device that is connected to the Internet. The original Internet Protocol is known as IPv4, while IPv6 is the next generation Internet protocl with a significantly larger address space than IPv4. IPv4 has a 32-bit IP address while IPv6 has a 128-bit IP address. With IPv6, every device can have a unique address because of the larger address space, while IPv4 requires its addresses to be reused and masked. Finally, IPv6 supports autoconfiguration while IPv4 only supports DHCP or manual configuration.

The Internet Corporation for Assigned Names and Numbers **(ICANN)** is an internationally organized, non-profit corporation that is responsible for IP address space allocation, protocol identifier assignment, and several other databases related to the namespaces and numerical spaces of the Internet. They help coordinate how IP addresses are supplied to regional registries, who then distribute them to network providers. Overseeing the immense interconnected network of unique identifiers that allow computers on the Internet to find one another ensures the network's stable and secure operation.

#### TCP/IP ####

Transmission Control Protocol / Internet Protocol **(TCP/IP)** is a protocol that defines the details of how data is sent and received through network communications hardware. The responsibility of TCP/IP is to connect government is to route data in and out of each virtual IP port. The client-server model applies to TCP/IP as the "client" here is the computer (or other device) that needs to know the IP address of whatever server it wants to connect to, and the server only has to listen for connections and either accept or reject them when initiated by the client. Once a connection has been established between the client and the server, data can be sent in either direction and the connection remains open until either side terminates it.

Single stack protocols are very inflexible because any changes require changing the entire application and protocol software, so the solution used in networking is to create layered protocol stacks. Each layer performs a particular function and communicates with the levels above and below it. For a real-world example, suppose you need to send a package from a person in one office to another person in a different office. Splitting this task into different layers allos you to change any of the individual layers/tasks without it affecting all the others. It does not matter how each task before and after the current one is accomplished, as each layer is only focused on its current task.

The TCP/IP protocol suite uses a 4 layer model, and each layer uses different protocols. In the application layer of the TCP/IP protocol suite, many different types of applications can be run here. Internet browsers, email applications, file transfer applications, instant messaging applications, and other information sharing applications can all be run in this layer.

#### Internet Security ####

Hypertext Transfer Protocol **(HTTP)**, used to transfer data all over the internet, is an application layer protocol for distributed, collaborative, hypermedia information systems. It supports the client-server model as the internet browser you are using is the client, and entering the name of the website you would like to visit means you are sending a request to a web server.

Secure HTTP **(HTTPS)** is an extension of HTTP used for secure communication over a network and is widely used on the Internet. It is encrypted using Transport Layer Security **(TLS)**, formerly called Secure Sockets Layer **(SSL)**, which encrypts an HTTP message prior to transmission and decrypts a message upon arrival. They keys for this symmetric encryption are generated uniquely for each connection and are based on a shared secret negotiated by the server and client before the first byte of data is transmitted. This negotiation is both secure and reliable, meaning attackers cannot access it or modify the communications without being detected.

#### Securing your Web Browser ####

Securing your web browser prevents numerous computer problems such as malware, spyware, and viruses that can steal your information, slow it down significantly, or make your software vulnerable to attackers in other ways. Without securing your browser, there is an increased chance that clicking links that you are unfamiliar with, going to websites that are not secure, or many other actions could cause your computer to be compromised, exploited, or disabled permanently.

While there are many factors that could cause your system to be vulnerable, one of the most well-known risks are cookies. They are files placed on your system to store data for specific websites. Cookies can contain any information that a website is designed to place in it, such as information about previously visited websites or credentials for accessing the site. They are designed to be readable only by the website that created them, and they are cleared either when the browser is closed or until the browser settings specify that they be deleted.

### Internet Programming ###

#### World Wide Web Consortium ####

Tim Berners-Lee is the inventor of the World Wide Web, and he also wrote the first web server and first client program. He also created the World Wide Web Consortium **(W3C)**, which is an international community consisting of full-time staff, industry experts, and other groups that all come together to develop standards for the world wide web. Berners-Lee recognized that standardizing the internet is important to web development because it helps lead the web to its full potential. By adapting the protocols and guidelines set by the W3C, software developers can ensure their programs work with all latest technologies. When browsers conform to W3C standards, it also helps web pages appear consistent across other browsers.

W3C standards are meant to maximize consensus about the content of a technical report, to ensure high technical and editorial quality, and to earn endorsement by W3C and the community as a whole. For example, W3C has standards which focus on technologies that enable Web access anywhere, anytime, and on any device. In this age of unprecedented technical advancement, having the capability to access the Internet on not only your phone, but your iPad, your smart watch, your video game console, your television, and even your car is expected when developing something new today. Therefore, W3C promotes "One Web" that is available on any device, and W3C's Mobile Web Initiative helps ensure the best user experience on mobile devices, taking into consideration device capabilities, location, and other context information.

#### HTML5 and CSS ####

Hyper Text Markup Language **(HTML)** and Cascading Style Sheets **(CSS)** both work together to create a webpage. HTML is responsible for dictating the structure and text of the page, while CSS is responsible for the style of it. Writing HTML allows you to create and modify where each part of your page are located as well as the text that makes up the page. CSS adds design to your HTML, including font sizes, background and font colors, padding and margins, and numerous other style elements. To design my webpage, I first used HTML to write my webpage's title, subheading, paragraph, image, and accompanying link. However, at that point, the page would be unorganized and almost unreadable, so I added style elements using internal CSS. There are three main ways to add CSS, and internal means you add your code to the heading section of your HTML using style tags. I gave each of my sections a class name in order to easily give them unique styles.

#### HTML and XML #####

While both HTML and eXtensible Markup Language **(XML)** are used to create web pages and web applications, there are key differences between the two. HTML is a static markup language that is more about presentation of data, while XML, which provides framework to define markup languages, mainly focuses on transfer of data. Finally, XML tags are extensible and user-defined, whereas HTML has predefined and limited tags.

### Components of a URL ###

1. **Scheme**: *(https)* - Every URL begins with this in order to tell your browser what type of address it is so the browser connects to it correctly, although it is not always being displayed.

2. **Domain**: *(www.amazon.com)* - This is the most prominent part of a web address, and every page on that site will usually have the same domain name. Each part of the domain name is separated by a period.

3. **Top Level Domain**: *(.edu)* - The domain on the right of the period, usually .com, .gov, .org, or .edu depending on the type of website.

4. **Default Page**: *(no file path provided)* - Usually results in the browser loading the home page of the website. 

5. **Parameters**: *(result of search)* - A string of characters after the file path that begin with a question mark is the **parameter string**, and it usually is displayed after a search by the user.

6. **Anchor**: *(specific location on a page)* - This tells your browser to scroll or to load a specific part of the page, and it usually begins with a hashtag which operates like a bookmark.

## Conclusion ##

Unit 6 revolved around understanding Internet architecture, how protocols play a part in it, and explaining why it is important to secure your web browser. We were also able to practice creating a simple HTML webpage with CSS while using a relative file path to add an image to the page. While I am currently taking a class dedicated to working with HTML and CSS, this was definitely a nice refresher on the basics. I am excited to see how we close this course in the next couple of weeks as we near the end of the semester.
