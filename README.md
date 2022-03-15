# CV HTML website
## Description

This is a HTML based Website made with the purpose of practice and learn front-end Web development.

I built it like a CV, it has all the skills that I had at the moment, i used a table to make some of the content of the page more soft to the eyes.

This is the code snippet that i used to make the table:

```
        <h3>Skills</h3>
        <table cellspacing="10">
            <tr>
                <td>
                    <table>
                        <tr>
                            <tr>
                                <td>App Development</td>
                                <td>⭐⭐⭐⭐</td>
                            </tr>
                            <tr>
                                <td>Database Development</td>
                                <td>⭐⭐⭐</td>
                            </tr>
                        </tr>
                    </table>
                </td>
                <td>
                    <table>
                        <tr>
                            <td>Web Development</td>
                            <td>⭐⭐</td>
                        </tr>
                        <tr>
                            <td>Android Development</td>
                            <td>⭐</td>
                        </tr>
                    </table>
                </td>
            </tr>
        </table>
```

I did a link between diferents HTML files too, this is the code snippet:

```
  <strong><a href="hobbies.html">My Hobbies</a></strong>
  <strong><a href="contact.html">Contact Information</a></strong>
```

And i did a  kinda form with a mailto to contact me directly, here is the code snippet i did for this purpose:

```
    <form action="mailto:fernandoarturo06@gmail.com" method"post" enctype="text/plain" >
        <label for="">Your Name: </label>
        <input type="text" name="yourName" id=""><br>
        <label for="">Your Email:</label>
        <input type="email" name="yourEmail" id=""><br>
        <label for="">Your Message: </label><br>
        <textarea name="yourMessage" id="" cols="30" rows="10"></textarea><br>
        <input type="submit" value="Submit">
    </form>
```
