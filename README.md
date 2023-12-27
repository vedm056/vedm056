<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>jQuery UI Tab with Search</title>
    <link rel="stylesheet" href="https://code.jquery.com/ui/1.12.1/themes/base/jquery-ui.css">
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://code.jquery.com/ui/1.12.1/jquery-ui.js"></script>
       <style>
        #clickergame{
        margin-top: -800px;
        margin-left: 800px;
        }
        body {
    margin: 0;
    padding: 0;
    display: grid;
}
        #tabs ul {
            list-style-type: none;
            padding: 0;
            background-color: black;
        }
        #tabs ul li {
            padding: 10px;
            cursor: pointer;
        }
        #tabs ul li:hover {
            background-color: cadetblue;
        }
        #tabs ul li:active {
            background-color: black;
        }
        #searchBar{
            background-color: black;
            margin-left: 0cap;
            margin-right: 0cap;
            color:white;
            display: grid;
    grid-template-columns: 1fr;
    justify-items: center;
    align-items: center;
    background-color: #000000;
    width: 100%;
    height: 50px;
    border: none;
    border-radius: 0px;
    padding: 0 20px;
    font-size: 18px;
    outline: none;
    text-align: center;
        }
        #searchBar2{
            margin-top:20px;
            width:46.5%;
            background-color: black;
            color:white;
    background-color: #000000;
        }
        #searchBar2.placeholder{
    padding: 20 60px;
    font-size: 18px;
    outline: none;
    text-align: center;
        }
        p{font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;text-decoration:wavy;font-size:15px;font-stretch:ultra-condensed;}
        #cringeendh1{
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;text-decoration:wavy;
            font-size:100px;
            font-stretch:ultra-condensed;
        }
        #colorDiv{
            height:200px;
            width:200px;
        }
        #freddy {
  position: absolute;
  width: 20%;
  height: 20%;
  animation: freddy 5s infinite;
}

@keyframes freddy {
  0% {
    transform: rotate(0deg);
  }
  1% {
    transform: rotate(10deg);
  }
  2% {
    transform: rotate(20deg);
  }
  3% {
    transform: rotate(30deg);
  }
  4% {
    transform: rotate(40deg);
  }
  5% {
    transform: rotate(50deg);
  }
  6% {
    transform: rotate(60deg);
  }
  7% {
    transform: rotate(70deg);
  }
  8% {
    transform: rotate(80deg);
  }
  9% {
    transform: rotate(90deg);
  }
  10% {
    transform: rotate(100deg);
  }
  11% {
    transform: rotate(110deg);
  }
  12% {
    transform: rotate(120deg);
  }
  13% {
    transform: rotate(130deg);
  }
  14% {
    transform: rotate(140deg);
  }
  15% {
    transform: rotate(150deg);
  }
  16% {
    transform: rotate(160deg);
  }
  17% {
    transform: rotate(170deg);
  }
  18% {
    transform: rotate(180deg);
  }
  19% {
    transform: rotate(190deg);
  }
}
#divjournal{
  height:200px;
  width:500px;
  border: #000000 2px dashed;
  overflow-y:scroll;
}

    </style>
</head>
<body>        
    <input type="text" id="searchBar" placeholder="Search">
    <div id="tabs">
        <ul>
            <li><a href="#tab-1">the start of web development</a></li>
            <li><a href="#tab-2">about the web</a></li>
            <li><a href="#tab-3">programming languages</a></li>
            <li><a href="#tab-4">but why was the web created?</a></li>
            <li><a href="#tab-5">symbiosis in play</a></li>
            <li><a href="#tab2">cool things you can do with web development</a></li>
            <li><a href="#tab-6">bye!</a></li>
        </ul>
        <div id="tab-1">
            <input type="text" id="search-bar" placeholder="Search...">
            <button id="search-button">Search</button>
            <h1 id="introheading1">Intro</h1>
            <p>The World Wide Web, or simply the Web, is a global information system that allows users to access and share data through computers connected to the Internet. The Web was invented by Tim Berners-Lee, a British computer scientist, who was born in London in 1955. His parents were both mathematicians and computer scientists who worked on one of the first commercial computers, the Ferranti Mark I. Berners-Lee graduated from Oxford University in 1976 and worked as a software engineer for various companies. In 1984, he returned to CERN, a large particle physics laboratory in Switzerland, where he developed a program called Enquire that could store and link information using hypertext. In 1989, he proposed a "universal linked information system" that would use the Internet as a platform for sharing and accessing information across different computers and networks. He also developed the first web server, the first web browser, and a document formatting language called HTML (Hypertext Markup Language). The Web was initially designed to meet the need for automated information-sharing among scientists in different universities and institutes around the world, but it soon became popular among the general public as well. The Web revolutionized the way people communicate, learn, work, and entertain themselves online. The Web is not the same as the Internet, which is the physical network of computers and cables that carry data. The Web is one of the services that runs on top of the Internet, along with others such as email and Usenet. The Web consists of billions of web pages that are stored on web servers and can be accessed by web browsers using a protocol called HTTP (Hypertext Transfer Protocol). The web pages contain text, images, audio, video, and other multimedia content that can be displayed or played by the browser. The web pages can also contain links to other web pages or resources on the Web, creating a web of information that users can navigate and explore. Berners-Lee is widely recognized as the inventor of the World Wide Web and has received many honors and awards for his contribution. He is the founder and director of the World Wide Web Consortium (W3C), which oversees the continued development of the Web standards and technologies. He also co-founded (with Rosemary Leith) the World Wide Web Foundation, which works to advance the Web as a public good and a basic right. He is a professorial research fellow at the University of Oxford and a professor emeritus at the Massachusetts Institute of Technology (MIT). He is also involved in various initiatives to promote open data, digital rights, and social innovation on the Web. In 2004, he was knighted by Queen Elizabeth II for his pioneering work. He also received the Turing Award in 2016, which is considered the Nobel Prize of computing.</p>
            <h1 id="whoistimbernerslee?">But who's Tim Berners Lee?</h1>
            <p>Sir Timothy John Berners-Lee is an English computer scientist widely known as the inventor of the World Wide Web. He was born on June 8, 1955, in London, England. He received a degree in physics from the Queen's College, Oxford, in 1976 and went on to work as an engineer at Plessey Telecommunications. In 1980, he moved to Switzerland to work at the European Organization for Nuclear Research (CERN), where he conceived of the idea of the World Wide Web. The World Wide Web was invented in 1989 as a way for researchers to share and access information electronically. Before its development, the internet was primarily used by academic and scientific communities. Berners-Lee's innovation allowed for the creation of a global network of information, which revolutionized the way people communicate and access information. He created the first web server, the first web browser, and the first website, which was hosted on his NeXT computer at CERN. Berners-Lee continued to develop the World Wide Web in the early 1990s, working with his colleagues at CERN to develop the first web standards and protocols. These included HTML (Hypertext Markup Language), HTTP (Hypertext Transfer Protocol), and URLs (Uniform Resource Locators), which are still used today. In 1993, he founded the World Wide Web Consortium (W3C), which develops and maintains web standards. The World Wide Web has had a profound impact on society, transforming the way people communicate, work, and access information. With its development, users could browse websites and access information from all over the world, making it easier than ever to communicate with people globally. The web also created new industries and job opportunities, including web design, web development, and online marketing. In addition to his work on the World Wide Web, Berners-Lee has been a vocal advocate for internet privacy and net neutrality. He has called for the development of a decentralized web, which would allow users to have more control over their data and prevent the centralization of the web by large corporations. In 2019, he launched the Contract for the Web, a global initiative to develop guidelines for a free and open web. Berners-Lee has received numerous honors and awards for his contributions to computer science and the web. He was knighted by Queen Elizabeth II in 2004, and in 2016 he received the IEEE Medal of Honor, one of the highest honors in the field of engineering. In 2017, he was awarded the Turing Prize, often referred to as the "Nobel Prize of Computing," for his invention of the World Wide Web. In conclusion, Sir Timothy Berners-Lee is one of the most influential figures in the history of computer science and the internet. His invention of the World Wide Web transformed the way people communicate and access information, and his ongoing work to promote internet privacy and a decentralized web continues to have a significant impact on society. He is a true pioneer in his field, and his contributions will continue to be felt for generations to come.</p>
        </div>
        <div id="tab-2">
            <h1>More info about the web</h1>
            <p>The year 2020 was a year like no other in many ways, and the web played a significant role in helping people stay connected and informed during the pandemic. The COVID-19 pandemic forced people to stay indoors and rely heavily on the internet for work, education, entertainment, and social interaction. As such, the web in 2020 played a critical role in shaping life as we know it. Firstly, one of the most striking things about the web in 2020 was how it brought people together despite physical distance. With the pandemic forcing people to work and learn from home, video conferencing and other online tools became the norm for virtual discussions, meetings, and classes. For instance, the video conferencing app, Zoom, became a household name in 2020, with people using it not just for work meetings, but also virtual family reunions, birthday parties, and baby showers. Secondly, the pandemic had a significant impact on e-commerce and online shopping behavior. With many stores closing their doors, people shifted their spending online, resulting in a surge in e-commerce activity. According to Adobe's Digital Economy Index, online shopping during the pandemic saw a 49% increase in spending compared to 2019. Thirdly, 2020 was a year of innovation in the tech industry with companies seeking to find new ways to meet the demands of a pandemic-riddled world. For instance, with many countries going into lockdown to curb the spread of the virus, people turned to fitness apps and online video workouts to keep their fitness goals in check. As such, many fitness apps, including Nike Training Club and Runtastic, saw a surge in subscription numbers. Fourthly, the year 2020 saw social media platforms becoming even more powerful and influential than ever before. With people mostly indoors, social media platforms became the go-to source for people to consume news, participate in conversations, and share their experiences. During the pandemic, platforms like Twitter, Facebook, Instagram, and TikTok were critical in providing space for people to stay connected. Fifthly, collaboration and productivity tools witnessed a significant shift in usage as more people transitioned to remote working. With people working from home, collaboration tools like Slack, Asana, and Trello were essential in keeping employees connected and ensuring they met their project timelines. Lastly, the web in 2020 saw a significant increase in misinformation and fake news. From the initial speculation around the origin of the virus to conspiracy theories around vaccines, the internet proved to be an outlet for spreading false information. Platforms like Facebook and Twitter struggled to contain this misinformation, leading to calls for the regulation of online content. In conclusion, 2020 was a year that placed the web at the center of daily life for many people. From enabling remote work and learning to keeping people connected socially, the internet proved its importance as a vital tool in times of crisis. At the same time, with the rise of fake news and disinformation, the web also highlighted the need for better regulation of online content.</p>
        </div>
        <div id="tab-3">
            <h1>Some programming languages you might find are:</h1>
            <div id="tabsx1">
            <ul>
                <li><a href="#tab-11">Lua</a></li>
                <li><a href="#tab-22">HTML5</a></li>
                <li><a href="#tab-33">PHP & mySQL</a></li>
                <li><a href="#tab-44">Ruby</a></li>
                <li><a href="#tab-55">Java</a></li>
                <li><a href="#tab-66">V</a></li>
                <input type="text" id="searchBar2" placeholder="SearchTabs">
            </ul>
            <div id="tab-11">a
              a
                <h2>A little bit about Lua</h2>
                <p>Lua is a dynamic and powerful programming language that is designed to be lightweight and embeddable. It is an open-source language that was originally developed as a scripting language for games, but it has expanded to many other areas such as web development, mobile applications, and scientific computing. Lua has become increasingly popular due to its simplicity, speed, and flexibility. One of the unique features of Lua is its ability to extend and customize itself with C or C++ programming libraries. This allows programmers to create efficient and powerful applications with ease. Its syntax is easy to understand and learn, making it an excellent choice for beginners. Despite its lightweight design, Lua is capable of handling complex tasks effortlessly, making it a strong choice for high-performance applications. Overall, Lua is a versatile language that can be used for a wide range of applications, making it an excellent choice for developers looking to create efficient and powerful applications.</p>
            </div>
            <div id="tab-22">
                <h2>A little bit about HTML5</h2>
                <p>HTML5 is a markup language used in web development to create and structure content for websites. It is the latest version of HTML and includes new features that make it easier for developers to create dynamic and interactive web pages. HTML5 supports multimedia elements, such as video and audio, without the need for plugins, and includes new form elements to help improve user experience. It also provides improved compatibility with mobile devices and supports responsive web design, allowing websites to adapt to different screen sizes. With its many features and benefits, HTML5 has become one of the most widely used programming languages in web development today.</p>
            </div>
            <div id="tab-33">
                <h2>A little bit about PHP</h2>
                <p>PHP is a widely used scripting language that is designed specifically for web development. The language is known for its flexibility, ease of use, and compatibility with almost all web servers. PHP is an open-source, server-side scripting language, which is used to create interactive and dynamic web pages and applications. Its syntax is designed to be easy to understand and learn, and it is suitable for seasoned programmers and beginners alike. The language is used to create websites, ecommerce sites, content management systems, blogs, and many other types of web applications. It is compatible with many databases such as MySQL, PostgreSQL, and Oracle. Furthermore, PHP is widely supported by hosting providers and is available on many platforms, making it accessible to developers worldwide.</p>
                <h2>But what's mySQL?</h2>
                <p>MySQL is an open-source relational database management system that uses SQL (Structured Query Language) for managing and manipulating data. Developed by MySQL AB and later acquired by Sun Microsystems, it has become one of the most popular database management systems used by businesses, websites, and software developers. MySQL programming language is very easy to learn and use, making it a popular choice for beginners and experienced programmers alike. It offers a range of features that allow users to quickly and easily create and manage complex databases. MySQL is also highly scalable and can handle large amounts of data, making it ideal for managing data-intensive applications. Overall, MySQL is a powerful, reliable, and flexible programming language that provides users with a range of tools for managing complex data structures.</p>
            </div>
            <div id="tab-44">
                <h2>A little bit about Ruby</h2>
                <p>Ruby is a high-level, interpreted programming language that was first released in Japan in 1995 by Yukihiro "Matz" Matsumoto. It is known for its elegant, simple syntax, which focuses on reducing the amount of boilerplate code required to accomplish common tasks. Ruby is an object-oriented language, which means that everything in Ruby is an object, including numbers, strings, and even methods themselves. This object-oriented approach allows for greater flexibility and modularity in programming. Ruby is also a dynamically typed language, which means that variable types are determined at runtime, rather than being explicitly defined. This can make Ruby code quicker to write and more flexible, but can also introduce potential bugs if not carefully managed. Despite its simplicity and ease of use, Ruby is a powerful and versatile language that is used in a wide variety of applications, including web development (with the popular Ruby on Rails framework), desktop applications, and even games.</p>
            </div>
            <div id="tab-55">
                <h2>A little bit about java</h2>
                <p>Java is a popular object-oriented programming language that was first released in 1995 by James Gosling and his team at Sun Microsystems. It has since become one of the most widely used programming languages in the world, thanks to its versatility, reliability, and ease of use. Java allows developers to write code that can run on virtually any platform or operating system, making it a popular choice for creating web apps, mobile apps, desktop applications, and games. Its syntax is similar to that of C++, but with several key differences that make it more suitable for large-scale software development projects. Some of the features that make Java so popular include its automatic garbage collection, which makes memory management easier, its support for multithreading, which enables programs to run more efficiently on modern hardware, and its robust set of libraries and frameworks, which provide developers with the tools they need to build complex applications. Whether you're a seasoned programmer or just starting out, Java is a great language to learn.</p>
            </div>
            <div id="tab-66">
                <h2>A little bit about V</h2>
                <p>V is a modern programming language that was designed to improve upon the shortcomings of other popular languages. Its syntax is concise and easy to read, making it a great language for beginners to learn. V is also extremely fast, which makes it ideal for performance-critical applications. Additionally, V is designed to be very secure, with built-in protection against common security vulnerabilities like buffer overflows. Another unique feature of V is its ability to generate cross-platform binaries, which means that code written in V can be compiled for a wide range of operating systems without requiring any changes. Overall, V is an exciting new programming language that is well worth checking out for anyone interested in modern software development.</p>
            </div>
            </div>
        </div>
        <div id="tab-4">
            <input type="text" id="search-bar2" placeholder="Search answers">
            <button id="search-button2">Search</button>
            <h1>Here is why then web was created:</h1>
            <p>The World Wide Web, also known as the "Web", is a collection of interconnected documents and resources, linked by hyperlinks and URLs, accessible via the Internet. It is now an indispensable part of our daily lives, from searching for information to shopping, socializing, and entertainment. However, the Web was not always there, and it was not created for commercial or entertainment purposes. In this essay, we will explore the history and reasons behind the creation of the Web. In the early 1990s, the Internet was primarily used for email, file transfer, and remote access to mainframe computers. However, there was no easy way to access and share information or publish content online. In 1989, a British computer scientist named Tim Berners-Lee, who was working at CERN (the European Organization for Nuclear Research), came up with an idea to solve this problem: a system of documents linked together by hyperlinks, accessible through a browser and based on a standardized markup language. He called this idea the World Wide Web. The main purpose of the Web was to facilitate scientific collaboration and information sharing between researchers and institutions. Berners-Lee wanted to create an open, decentralized system where anyone could publish and access information, regardless of their location or technology. He envisioned the Web as a platform for building knowledge and connections among people from different countries, cultures, and disciplines. To make this vision a reality, Berners-Lee designed several crucial components of the Web, including HTML (hypertext markup language), HTTP (hypertext transfer protocol), and the first web browser, called WorldWideWeb. He also launched the first Web server at CERN and encouraged others to adopt his standards and tools. The Web quickly gained popularity and expanded beyond its original scientific audience. People from all walks of life began to create websites, blogs, and online communities, sharing everything from personal opinions to professional expertise. The Web enabled a new era of free expression, public discourse, and entrepreneurship, empowering individuals and small businesses to reach global audiences without intermediaries. However, the Web also faced many challenges and controversies as it grew. One of the most significant issues was the lack of regulation and security. The Web was an open platform that allowed anyone to create and publish content, but it also made it easy for malicious actors to spread false information, viruses, and scams. Moreover, the Web's reliance on advertising and data collection raised concerns about privacy, surveillance, and discrimination. Despite these challenges, the Web has continued to evolve and improve, adapting to new technologies and social norms. Today, it is not just a tool for information and communication but also a culture, a market, and a network of digital relationships. The Web has transformed the way we live, learn, work, and play, connecting billions of people and devices around the world. In conclusion, the Web was created to solve the problem of sharing and accessing information online. Its inventor, Tim Berners-Lee, wanted to create an open, decentralized system that would promote scientific collaboration and knowledge exchange. The Web quickly expanded beyond its original purpose, becoming a platform for expression, innovation, and social interaction. Although the Web faces many challenges, it remains an essential part of our lives and a symbol of the power of technology to connect, educate and empower people.</p>
            <h1>Where there any other reasons why the web was originally created?</h1>
            <p>Yes, the original purpose of the web was to facilitate communication among scientists and researchers, specifically physicists who needed a more efficient way to share data and research findings. Tim Berners-Lee, the inventor of the web, wanted to create a system that could easily connect various research facilities and universities, enabling scientists to collaborate and share information more effectively. Additionally, Berners-Lee envisioned the web as a way to democratize information and make it accessible to everyone, regardless of their geographic location or social background.</p>
            <h1>If it is already created why is it still being advanced?</h1>
            <p>The web, as we know it today, has indeed come a long way since its inception. It has revolutionized the way we communicate, access information, and conduct business. However, despite its remarkable progress, the web continues to evolve and advance at a rapid pace. This ongoing advancement is driven by several key factors. Firstly, technology is constantly evolving. The web is built upon a complex stack of technologies, including HTML, CSS, JavaScript, and various protocols and standards. As new technologies emerge and existing ones improve, it becomes possible to enhance the capabilities and performance of the web. For example, the introduction of HTML5 brought new features like video and audio support, canvas for graphics rendering, and improved forms and input controls, enabling richer and more interactive web experiences. Secondly, user expectations and demands are continuously evolving. As users become more sophisticated and tech-savvy, they expect more from their online experiences. They demand faster load times, responsive designs, seamless interactions, and engaging multimedia content. To meet these expectations, web developers and designers need to constantly push the boundaries of what is possible and explore new techniques and tools to deliver exceptional user experiences. Thirdly, the web is not just a static medium for information dissemination anymore. It has become a platform for complex applications and services. With the rise of cloud computing, web applications have gained immense popularity, providing powerful functionality that was traditionally only available through desktop software. This shift towards web-based applications has created a need for more advanced web technologies and frameworks that can handle complex data processing, real-time collaboration, and offline capabilities. Moreover, the web is a global network, and its advancements are not limited to a single organization or group of individuals. It is an open platform that encourages collaboration, innovation, and standardization. Organizations such as the World Wide Web Consortium (W3C) and open-source communities play a vital role in driving the advancement of the web by developing and maintaining standards, specifications, and open-source projects that shape its future. Lastly, security and privacy concerns are constant challenges on the web. As the web becomes more intertwined with our daily lives, it becomes increasingly important to ensure the security and privacy of users' data and interactions. New vulnerabilities and threats emerge regularly, and advancements in web technologies are necessary to address these challenges and provide a more secure and private online environment. In conclusion, the web is constantly being advanced because of the ongoing evolution of technology, evolving user expectations, the need for advanced web applications, the collaborative nature of the web, and the constant challenges of security and privacy. These factors drive the continuous improvement and innovation in web technologies, making the web a more powerful, secure, and user-friendly platform for various applications and services.</p>
        </div>
        <div id="tab-5">
            <input type="text" id="search-bar3" placeholder="Search answers">
            <button id="search-button3">Search</button>
            <h1>What is human/web symbiosis?</h1>
            <p>Human-Web symbiosis refers to the deep and intricate relationship between humans and the World Wide Web, where both entities mutually benefit and rely on each other for various aspects of modern life. It is a concept that highlights the interdependence and synergy between humans and the web, shaping the way we communicate, access information, conduct business, and interact with the digital world. This essay explores the key aspects and implications of the Human-Web symbiosis. At its core, the Human-Web symbiosis is rooted in the idea that the web is an extension of human capabilities and intellect. It acts as a vast repository of knowledge and a platform for communication, allowing individuals to access and share information with unprecedented ease and speed. The web has become an integral part of our daily lives, serving as a primary source of news, entertainment, social interaction, and professional development. One of the fundamental aspects of the Human-Web symbiosis is the democratization of knowledge and information. The web has broken down barriers to access, enabling individuals from all walks of life to explore and educate themselves on a wide range of topics. Online educational resources, such as massive open online courses (MOOCs), provide opportunities for lifelong learning and skill development, irrespective of geographical or socioeconomic constraints. This symbiotic relationship empowers individuals to acquire knowledge, enhance their skills, and contribute to the global knowledge pool. The Human-Web symbiosis also encompasses the concept of collective intelligence. The web enables collaboration and collective problem-solving on a global scale. Open-source software development, crowdsourcing, and online communities foster the sharing of ideas and expertise, leading to the creation of innovative solutions and the advancement of various domains. Through platforms like GitHub and Stack Overflow, developers collaborate, learn from each other, and collectively improve the quality of software. This collaboration extends beyond technical domains, with social platforms enabling individuals to exchange ideas, mobilize for social causes, and drive positive change. Furthermore, the Human-Web symbiosis has transformed the way we conduct business and commerce. E-commerce platforms have revolutionized the retail industry, providing consumers with convenience, choice, and personalized experiences. The web serves as a global marketplace, connecting buyers and sellers from around the world. Businesses leverage the web for marketing, customer engagement, data analysis, and supply chain management, enabling them to reach a wider audience and optimize their operations. This symbiotic relationship has facilitated economic growth, job creation, and entrepreneurship. However, the Human-Web symbiosis is not without its challenges and implications. The increasing reliance on the web has raised concerns about privacy, security, and the ethical use of personal data. Internet surveillance, data breaches, and the manipulation of information are pressing issues that need to be addressed to maintain trust and ensure the continued symbiotic relationship between humans and the web. Additionally, the digital divide and unequal access to the web pose challenges in realizing the full potential of the Human-Web symbiosis. Efforts should be made to bridge this divide and ensure that everyone can benefit from the opportunities offered by the web. In conclusion, the Human-Web symbiosis represents a profound integration of humans and the World Wide Web, resulting in a mutually beneficial relationship that shapes various aspects of modern life. The web acts as an extension of human capabilities, enabling access to knowledge, fostering collaboration, transforming commerce, and driving innovation. However, it also presents challenges that need to be addressed to ensure privacy, security, and equal access. As we navigate the symbiotic relationship between humans and the web, it is essential to strike a balance that maximizes the benefits while mitigating the risks, ultimately fostering a digital ecosystem that empowers individuals, promotes inclusively, and drives positive societal change.</p>
            <h1>What is web/robot symbiosis?</h1>
            <p>Web/robot symbiosis refers to the integration and collaboration between the World Wide Web and robotic systems, where both entities work together to enhance and extend human capabilities in various domains. It represents a convergence of web technologies and robotics, enabling robots to access and interact with web-based resources and services, while the web provides a platform for sharing and analyzing data collected by robots. This essay explores the key aspects and implications of web/robot symbiosis. At its core, web/robot symbiosis leverages the power of the web to enhance the capabilities of robots. Robots are physical machines that can perform tasks autonomously or under human control. By integrating web technologies, robots can tap into the vast amount of information available on the web, enabling them to access real-time data, learn from online resources, and communicate with other devices and systems. This integration expands the knowledge base and capabilities of robots, enabling them to perform complex tasks and adapt to dynamic environments. One of the fundamental aspects of web/robot symbiosis is the ability of robots to access and utilize web-based resources and services. For example, robots can leverage cloud computing platforms to offload computationally intensive tasks, such as image recognition or natural language processing, to remote servers. This allows robots to benefit from powerful computational resources and advanced algorithms that may not be feasible to run on their own hardware. Additionally, robots can access web APIs to retrieve data from various sources, such as weather forecasts, traffic information, or stock market data, enriching their decision-making capabilities.  Moreover, the web serves as a platform for sharing and analyzing the data collected by robots. Robots generate vast amounts of sensor data, including images, videos, sensor readings, and environmental data. By leveraging web technologies, this data can be shared and analyzed in real-time, enabling collaborative decision-making and knowledge sharing. For instance, robots deployed in disaster response scenarios can transmit live video feeds and sensor data to a central command center, where experts can remotely analyze the data and provide guidance to the robots on the ground. The integration of the web and robots also enables the concept of collective robotics and distributed intelligence. Robots can communicate and collaborate with each other through the web, sharing information, coordinating actions, and collectively solving tasks. This aspect of web/robot symbiosis opens up possibilities for swarm robotics, where a group of robots work together to achieve a common goal, whether it's exploring an unknown environment, performing search and rescue operations, or coordinating a complex manufacturing process. Furthermore, web/robot symbiosis has implications in various domains, including healthcare, logistics, agriculture, and manufacturing. In healthcare, robots can leverage web-based medical databases, research articles, and patient records to assist in diagnosis, treatment planning, and remote patient monitoring. In logistics, robots equipped with web connectivity can optimize routes, track inventory, and communicate with other devices in the supply chain. In agriculture, robots can access web-based weather forecasts, soil data, and crop information to optimize irrigation, fertilization, and pest control. In manufacturing, robots can leverage web-based product information, quality control systems, and real-time analytics to improve efficiency and quality. However, web/robot symbiosis also raises ethical and security concerns. The integration of robots with the web introduces vulnerabilities and potential risks, such as unauthorized access to robot systems, data breaches, and privacy violations. It is crucial to address these concerns through robust security measures, encryption protocols, and ethical guidelines to ensure the safe and responsible use of web-connected robots. In conclusion, web/robot symbiosis represents a powerful integration of web technologies and robotic systems, enabling robots to access, utilize, and contribute to the web. This symbiotic relationship enhances the capabilities of robots, enables collaboration and distributed intelligence, and has implications in various domains. However, it also brings about ethical and security challenges that need to be addressed. As we continue to explore the potential of web/robot symbiosis, it is vital to strike a balance that maximizes the benefits while ensuring the safety,</p>
        </div>
        <div id="tab2">
            <h1>cool things you can do with web development:</h1>
            <h2>Color Sliders:</h2>
            <div id="colorDiv"></div>
  <input type="range" id="redSlider" min="0" max="255" value="0">
  <input type="range" id="greenSlider" min="0" max="255" value="0">
  <input type="range" id="blueSlider" min="0" max="255" value="0">
  <p>to use these color sliders you have to first change one of the sliders and release your mouse for this function to work.</p>
            <h2>Websites in Websites:</h2>
            <embed style="height: 300px;width:500px;" src="DeskwarsOfficialSite.html"></embed>
            <p style="width:40%;margin-top:-10px">over here the Deskwars Official website(in making) has been embedded so you can use it in this website!! the reason it is so small and confusing is because only a portion of it is shown. you can think of that as if the Deskwars official website was behind this one and there would be a window you could use to see it. then you can move this website to see the Deskwars website.</p>

            <div id="clickergame">
            <h2>extremely basic clicker game:</h2>
            <p>Click the button to earn points!</p>
  <button id="clickButton1">Click</button>
  <p>Your score is: <span id="score1"></span></p>
  <p>there is just one problem with this clicker game: it is very very basic and boring so people tend to play clicker games that are more intriguing like this one:</p>

  <p>Click the button to earn points!</p>
  <button id="clickButton">Click</button>
  <p>Your score is: <span id="score"></span></p>

  <div id="upgrades">
    <h2>Upgrades</h2>
    <ul>
      <li>
        <button id="upgrade1">Upgrade 1</button>
        <p>Increases your click speed by 10%</p>
      </li>
      <li>
        <button id="upgrade2">Upgrade 2</button>
        <p>Increases your click damage by 20%</p>
      </li>
      <li>
        <button id="upgrade3">Upgrade 3</button>
        <p>Increases your health by 50%</p>
      </li>
    </ul>
  </div>
  <p>In this one it has more things to do but since I am not that good at coding I couldn't make a complex one.</p>
  </div>
        <h2 style="margin-top:50px;width:50%;">I can make an image that constantly moves using code!!!!</h2>
        <img style="margin-top:30px;" id="freddy" src="https://th.bing.com/th/id/OIP.hTaIOCbqRzNTvRWz9bMg4QHaHa?w=166&h=180&c=7&r=0&o=5&dpr=1.5&pid=1.7" alt="freddy fazbear!">
        <h2 style="margin-left:50%;width:50%;margin-top:-30px;">here is a small journalizing tool you could use!</h2>
        <div style="margin-left:50%;width:50%;">
        <form>
          <input type="text" id="textbox2"/>
          <button type="button" onclick="copyText()" id="copytextbuttonforjournal">Copy Text</button>
          <button type="button" onclick="clearDiv()" id="cleartextbuttonforjournal">Clear Div</button>
          </form>
          <div id="divjournal"></div>
          <h2>Image Montage</h2>
          
        </div>
          <script>
            function copyText() {
              var textbox = document.getElementById("textbox2");
              var div = document.getElementById("divjournal");
              div.innerHTML += textbox2.value;
          textbox2.value;
            }
            
            function clearDiv() {
              var div = document.getElementById("divjournal");
              div.innerHTML = "";
            }
            </script>
            
        </div>
        <div id="tab-6">
            <h1 id="cringeendh1">Thank you for listening to my presentation!!!</h1>
            <p style = "text-align:center; font: 8px verdana white; background-color:rgb(30, 255, 0);margin-top:-30px;">I am not sure if you noticed but the reason I programmed a website for my ISP was because is relates to the topic of web development.</p>
        </div>
    </div>
<script>
 var score1 = 0;

$("#clickButton").on("click", function() {
  score1++;
  $("#score").html(score1);
});

// Add a timer that increases the score by 1 every second.
var timer = setInterval(function() {
  score1++;
  $("#score").html(score1);
}, 1000);

// Add event listeners to the upgrade buttons.
$("#upgrade1").on("click", function() {
  // Increase the click speed by 10%.
  score += score * 0.1;
  $("#score").html(score1);
});

$("#upgrade2").on("click", function() {
  // Increase the click damage by 20%.
  score += score * 0.2;
  $("#score").html(score1);
});

$("#upgrade3").on("click", function() {
  // Increase the health by 50%.
  score += score * 0.5;
  $("#score").html(score1);
});



         var score = 0;

$("#clickButton1").on("click", function() {
  score++;
  $("#score1").html(score);
});
         $(document).ready(function() {
      var redSlider = $("#redSlider");
      var greenSlider = $("#greenSlider");
      var blueSlider = $("#blueSlider");
      var colorDiv = $("#colorDiv");

      function updateColor() {
        var redValue = redSlider.val();
        var greenValue = greenSlider.val();
        var blueValue = blueSlider.val();
        var color = "rgb(" + redValue + "," + greenValue + "," + blueValue + ")";
        colorDiv.css("background-color", color);
      }

      redSlider.on("change", updateColor);
      greenSlider.on("change", updateColor);
      blueSlider.on("change", updateColor);
    });
        $(document).ready(function() {
            $("#tabs").tabs();
            $("#tabsx1").tabs();
            $("#searchBar").on("keyup", function() {
                var value = $(this).val().toLowerCase();
                $("#tabs ul li").filter(function() {
                    $(this).toggle($(this).text().toLowerCase().indexOf(value) > -1)
                });
            });
            $("#searchBar2").on("keyup", function() {
                var value2 = $(this).val().toLowerCase();
                $("#tabsx1 ul li").filter(function() {
                    $(this).toggle($(this).text().toLowerCase().indexOf(value2) > -1)
                });
            });
        });
    </script>
    <script>
        document.getElementById('search-button').addEventListener('click', function() {
            var searchBar = document.getElementById('search-bar');
            var searchText = searchBar.value.toLowerCase();
        
            var headings = document.querySelectorAll('h1');
            for (var i = 0; i < headings.length; i++) {
                var heading = headings[i];
                var headingText = heading.textContent.toLowerCase();
        
                if (headingText.includes(searchText)) {
                    heading.scrollIntoView(); // Scroll to the h1
                    break;
                }
            }
        });
        
        document.getElementById('search-bar2').addEventListener('keypress', function(event) {
            if (event.key === 'Enter') {
                document.getElementById('search-button2').click();
            }
        });
        document.getElementById('search-button2').addEventListener('click', function() {
            var searchBar = document.getElementById('search-bar2');
            var searchText = searchBar.value.toLowerCase();
        
            var headings = document.querySelectorAll('h1');
            for (var i = 0; i < headings.length; i++) {
                var heading = headings[i];
                var headingText = heading.textContent.toLowerCase();
        
                if (headingText.includes(searchText)) {
                    heading.scrollIntoView(); // Scroll to the h1
                    break;
                }
            }
        });
        
        document.getElementById('search-bar').addEventListener('keypress', function(event) {
            if (event.key === 'Enter') {
                document.getElementById('search-button').click();
            }
        });
        
        document.getElementById('search-button3').addEventListener('click', function() {
            var searchBar = document.getElementById('search-bar3');
            var searchText = searchBar.value.toLowerCase();
        
            var headings = document.querySelectorAll('h1');
            for (var i = 0; i < headings.length; i++) {
                var heading = headings[i];
                var headingText = heading.textContent.toLowerCase();
        
                if (headingText.includes(searchText)) {
                    heading.scrollIntoView(); // Scroll to the h1
                    break;
                }
            }
        });
        
        document.getElementById('search-bar3').addEventListener('keypress', function(event) {
            if (event.key === 'Enter') {
                document.getElementById('search-button3').click();
            }
        });
        </script>
</body>
</html>
