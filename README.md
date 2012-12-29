CSTL (Client Sided Tag Libs)

--What are TagLibs--

(X)HTML is a markup language providing elements – so called tags – to enable 
developers expressing what a specific piece of text means and in what kind of context it 
stands. So basically (X)HTML comes with a set of tags of it’s own, including some type of 
controls such as form fields etc. 
If you want to create complex controls such as menus, tab strips etc. you need to get 
your hands dirty in some client side scripting language such as JavaScript. This easily 
ends up to become either rather complicated, if you build the scripts yourself or messy if 
you try to reuse other people’s scripts – especially if a couple of them is combined. This 
is mainly due to JavaScript lacking a namespacing concept and document events are 
often used in conflict with each other. 
Client Side Tag Libs provide you with the right level of encapsulation so that reusing your 
work or other peoples components is possible without concens about collisions. At the 
same time it easily embeds these components into you pages using syntax you already 
know – custom tags. 

--Where TagLibs come from--
TagLibs are a technology branch from the J2EE world, where developers wanted to solve 
the exact same issues about namespace collision, easy maintainence and reusability on 
the server side. Tags would be processed completely on the server side by some 
application plattform and would spit out resulting HTML. 
While this would address the issues mentioned, it would also rely on a application 
platform existing – which may include licensing issues -, processing capabilities of the 
server used on each page load and bandwidth used since every interaction with a server 
side control would involve a new page refresh. 

--Why use TagLibs--
As web applications nowadays tend to go into the rich client direction more and more, 
the flickering page refreshes and the insufficient  scalability involved with server sided 
TagLib technologies leads one to find alternative ways. Ultimately its always about 
creating better user experiences. 
JavaScript has been around for quite a while now. Browsers have become mature enough 
to support DOM at a level which is usable to transport TagLibs to the client side. Given an 
appropiate Client Side TagLib architecture is in place as a developer you have a much 
better level of encapsulation and reusability of existing components by the build-onceuse-anywhere paradigm. As an application provider you can smile upon bandwidth 
savings and less processing power needed for a more attractive user experience. And as 
the end user you have a more reactive user interface, that allows you to do more 
complex things without a server roundtrip involved for every click you do. 
Another alternative is to use Macromedia Flex in coupling with a J2EE server. While the 
Macromedia Flash player claims to be installed on 98% of the clients out there and 
provide developers with a more stable technology than JavaScript, you may face pricing 
issues and fear a vendor lock-in when going down that road. 
