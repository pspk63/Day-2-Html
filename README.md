# HTML Learning Journey - Day 2

## Overview
Welcome to **Day 2** of learning HTML! In this session, we'll cover the basics of HTML and simple HTML tags.

### Topics Covered:
1. **Tags**:
    - Understanding tags like `<h1>`, `<p>`, `<br>`,`<hr>`,`<i>`,`<u>` and more.
3. **Practice Exercise**:
    - Build your first HTML file and display it in a web browser.

---

## Day 2 Code Example

Here’s a simple example of an HTML page that you'll create during this session:

## Live Preview

[![Live Preview](https://img.shields.io/badge/Live-Preview-brightgreen)](https://vimeo.com/1011032686)


```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Day-2</title>
</head>
<body>

    <!--Ancher-->
    <a href="www.nvpalemganesh.000.pe"> Visit Now </a><br><br>


    <!--img tag-->
    <img src="https://img.freepik.com/free-photo/portrait-viking-children-s-day-day-life_23-2151686400.jpg?size=626&ext=jpg" alt=" This  is Mother Love">

    <!--Order list-->
    <ol>
        <li>This Is Order List 1</li>
        <li>This Is Order List 2</li>
        <li>This Is Order List 3</li>

    </ol>


    <!--Unorder list-->
    <ul>
        <li>This Is unOrder List 1</li>
        <li>This Is unOrder List 2</li>
        <li>This Is unOrder List 3</li>

    </ul>



    <!--Tables-->
    <table border="3px;">
        <tr>
            <th>Roll No</th>
            <th>Name</th>
            <th>Age</th>
            <th>Branch</th>
        </tr>
        <tr>
            <td>21F91A4625</td>
            <td>Mahendra</td>
            <td>21</td>
            <td>Cse-cs</td>
        </tr>
    </table>
    <br><br>



    <!--Forms-->
    <form>
       
        <input type="text" placeholder="Enter your Name" required>
        <br><br>
        <input type="number" placeholder="Enter Your Age">
        <br><br>
        <input type="radio">Female
        <input type="checkbox">Male
        <br><br>
        <input type="reset">
        <input type="submit">
        <input type="range">
        <br><br>
        <input type="date">
    </form>


    <!--Sections-->
    <nav>
        <a href="#about">about</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h1>About</h1>
    </section>
    <section id="contact">
        <h3>Contact</h3>
    </section>

    <address>
        <p>Karedu</p>
    </address>

    <audio src="audio.mp3"></audio>

    <video src="video.mp4"></video>

    <iframe width="560" height="315" src="https://www.youtube.com/embed/N9uZ3S-1q-c?si=Nv1GbLH9nsJ3hnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

    <footer>
        all CopyRights are reserved &copy; i1 Industries
    </footer>
</html>
