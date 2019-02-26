"# demo-SpringInAction" 

**在线社交Spitter**

为了实现在线社交的功能，我们将要构建一个简单的微博（microblogging）应用。在很多方面，
我们所构建的应用与最早的微博应用Twitter很类似。在这个过程中，我们会添加一些小的变
化。当然，我们要使用Spring技术来构建这个应用。

因为从Twitter借鉴了灵感并且通过Spring来进行实现，所以它就有了一个名字：Spitter。再进一
步，应用网站命名中流行的模式，如Flickr，我们去掉字母e，这样的话，我们就将这个应用称为
Spittr。这个名称也有助于区分应用名称和领域类型，因为我们将会创建一个名为Spitter的
领域类。

Spittr应用有两个基本的领域概念：**Spitter（应用的用户）和Spittle（用户发布的简短状态更新**）。
当我们在书中完善Spittr应用的功能时，将会介绍这两个领域概念。在本章中，我们会构建应用
的Web层，创建展现Spittle的控制器以及处理用户注册成为Spitter的表单。
舞台已经搭建完成了。我们已经配置了DispatcherServlet，启用了基本的Spring MVC组
件并确定了目标应用。让我们进入本章的核心内容：使用Spring MVC控制器处理Web请求。