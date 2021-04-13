***LOCAL STORAGE FOR WEB APPLICATIONS***

 Local storage is one of the areas where the native client applications have held an advantage over web applications.

 Web applications have had none of these luxuries. Cookies invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data.

 There are some disadvantges of the web pages, here are some of them:

 1- Cookies are included with every HTTP request, which is slowing the application by repating the data.


 2- Cookies are included with every HTTP request, which sending data unencrypted over the internet (unless your entire web application is served over SSL).

 

 **Note: the most important thing that we want from the application that a storage space.**

 ***HTML5 STORAGE***

   Web Storage is specification refer to  “HTML5 Storage”, that was  part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” The naming situation is made even more complicated by some related, similarly-named, emerging standards that I’ll discuss later in this chapter.

                       HTML5 STORAGE SUPPORT
      IE	FIREFOX	SAFARI	CHROME	OPERA	IPHONE	ANDROID
       8.0+ 3.5+	4.0+	4.0+	10.5+	2.0+	2.0+
 

 How to store data using HTML5 STORAGE?

 HTML5 Storage is depend the  on named key/value pairs. Where you store data based on a named key, then you can retrieve that data with the same key. a string is a named key. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.