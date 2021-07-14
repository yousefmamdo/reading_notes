## form 
An HTML form is a section of a document containing normal content, markup, special elements called controls (checkboxes, radio buttons, menus, etc.), and labels on those controls. Users generally "complete" a form by modifying its controls (entering text, selecting menu items, etc.), before submitting the form to an agent for processing (e.g., to a Web server, to a mail server, etc.)

Here's a simple form that includes labels, radio buttons, and push buttons   
+ for ex:
<FORM action="http://somesite.com/prog/adduser" method="post">
    <P>
    <LABEL for="firstname">First name: </LABEL>
              <INPUT type="text" id="firstname"><BR>
    <LABEL for="lastname">Last name: </LABEL>
              <INPUT type="text" id="lastname"><BR>
    <LABEL for="email">email: </LABEL>
              <INPUT type="text" id="email"><BR>
    <INPUT type="radio" name="sex" value="Male"> Male<BR>
    <INPUT type="radio" name="sex" value="Female"> Female<BR>
    <INPUT type="submit" value="Send"> <INPUT type="reset">
    </P>
 </FORM>


 ## Define an HTML Table
![table](https://cdn.educba.com/academy/wp-content/uploads/2020/02/Nested-Table-in-HTML-output-4.2.png)
The <table> tag defines an HTML table.

Each table row is defined with a <tr> tag. Each table header is defined with a <th> tag. Each table data/cell is defined with a <td> tag.

By default, the text in <th> elements are bold and centered.

By default, the text in <td> elements are regular and left-aligned.

## lists

![table](https://media.gcflearnfree.org/content/5e46ef60397c182fec255f32_02_14_2020/lists.png)

HTML offers web authors three ways for specifying lists of information. All lists must contain one or more list elements. Lists may contain −

+ <ul> − An unordered list. This will list items using plain bullets.

+ <ol> − An ordered list. This will use different schemes of numbers to list your items.

+ <dl> − A definition list. This arranges your items in the same way as they are arranged in a dictionary.