# Difference between document and window object

### What are Document and Window Objects?

**Document Object:
        It represents the web page loaded in the browser window. It serves as an entry point to the content of the web page and provides methods and properties to manipulate the content, such as modifying elements, accessing the DOM tree, and handling events related to the document.

**Window Object:
        It represents the browser window that contains the Document object. It acts as a global object for JavaScript code running within the browser window, providing access to various browser-related functionalities, such as navigating to URLs, opening new windows, setting timeouts, and handling events related to the window itself.

### Differences Between Document and Window Objects


###Scope and Hierarchy 	

Document object : It is a child object of the Window object, it exists within the context of a window	

Window Object : Encapsulates everything within the browser window (Document object, frames, history, location, and more)

###Content Manipulation	

Document object : Providing methods to manipulate elements, create new elements, update styles, and modify the DOM structure	

Window Object : It offer some methods for interacting with the document (such as accessing forms or images), is more focused on browser-related actions like opening new windows, controlling navigation, and handling events like scrolling or resizing.

###Visibility	

Document object : visible content of the web page, including HTML elements, text, images, and other media.	

Window Object : Encompasses everything within the browser window, including the content (Document object) as well as browser-specific elements like toolbars, menus, and tabs.

###Lifecycle	

 Document object : Browser loads a new page and is destroyed when the page is closed or navigated away.	
 
 Window Object : Browser is opened and persists until the window is closed.

