# Assingmet - 4 
 - ## How do web browsers function?
    - The browser take your request sends it over the network to a server, the serever sends to back all the needed information and dislays the pages. There are 6 key element need to make your web browser function:
      1. User Interface: What is presented to the user to interact with (the addressbar, back & forworth bottons, tabs, etc.)
      2. Rendering Engine: The engines take in HTML and CSS documents and displays the visual representaion of the web page
         - HMTL: exists to make up markup (a system of annotating a document to describe its structure and presentation) our content
         - CSS: used to style and aminate our content 
      3. Bowerser Engine: Directs actions between; the user, the interface, the rendering engine, and external connumication with servers 
      4. Network: The user must communicate ovet the over the network to get content, asking for the necessary images and documents that make up the web page 
      5. JavaScript: A programing langauge needed to bring interative logic and functionality to our website
          - The browsers don't know what to deal with JavaScript so we need a JavaScript interpreter, browsers have to own interpreter
      6. Date Storage: Cookie and Local storage help us reatin state even when you refrsh the page 
- ## What is the DOM? (Document Object Model)
  - The DOM tree is a content tree created by the Rendering Engine after it has reads the HTML code sent by the Network. The DOM tree is conprised of DOM nodes. Nodes can be images, text blocks, buttons, ardered lists, ect. and any CSS styling association with the node are passed by the pasted by the engine. Now with all the necessary information in place a new tree is created the Render tree. After this is complete the information goes through a layout prosesses, each node is positioned on eht page with coordinated, the Render tree is gone ove with each node "painted" by the UI backend Layer, giving you your completed loaded web page. 
- ## What are the differences in: HTML, XML, XHTML?
  - HTLM (Hypertext Markup Language):
      - functions as the foundation and structure of a page's content
      - displays document nodes 
      - Standardized element and tagging system
  - XML (Extensible Markup Language):
      - stored in plain-text format, which simplifies data sharing
      - discribes document nodes 
      - no pre-defined tags (author must define and structure individually)
  - XHTML (Extensible Hypertext Markup Language):
      - nearly indentical the HTML, but has more **stict code** requirments
      - longer to write
      - easier to maintain
- ## What are the four essential elements every HTML page needs?  
    1.The <!DOCTYPE> declaration.    
    2. The < root > element.        
    3. The < head > element.     
    4. The < body > element.     
- ## What’s the purpose of the index.html page?
  - A majority of websites have a master HTML files call the index, the are typical multiple index file on a site, however atleast one of them is always the the home page.
  - The index.html is found at the root directory 
- ## What are the top naming practices for clean and organized code?
  - Naming files:
    - always need an index.html home folder
    - no spaces, no odd character
    - lowercase is recomened, if ypu are not using more than one word
    - use a consistent naming convention
    - always include an extention with all the file
  - Organzing files:
    - With in the 'Root' folder it's good to have subfolders for different aspect; Pages, images, CSS, sripts, of course the index.html is in on it's own. Type to keep eathing but the index.html file within the subfolder. 
