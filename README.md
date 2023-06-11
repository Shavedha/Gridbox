# EXPERIMENT 4 - Web-Layout using Gridbox
## AIM
To create a weblayout using Gridbox
## ALGORITHM
1. Set up the container to display as a grid with three columns and four rows.
2. Define the styles for the header, sidebar, main content, and footer divisions, including their grid placement, background colors, padding, and text styles.
3. Create a header division that spans all three columns.
4. Create a sidebar division that occupies the first column and second to fourth rows.
5. Create a main content division that spans the second and third columns and is placed in the second row. Lastly, create a footer division that spans all three columns.
## PROGRAM
```
<!DOCTYPE html>
<html>
<head>
  <style>
    
    body {
      margin: 0;
      padding: 0;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      grid-template-rows: auto 1fr auto;
      min-height: 100vh;
    }

    
    .header {
      grid-column: 1 / 4;
      background-color:rgb(116, 211, 130);
      padding: 20px;
      color:black;
      text-align: center;
      font-size: x-large;
    
    }

    .sidebar {
      grid-column: 1 / 2;
      grid-row: 2 / 4;
      background-color:rgba(233, 226, 34, 0.426);
      padding: 20px;
      
    }

    .main-content {
      grid-column: 2 / 4;
      grid-row: 2 / 3;
      background-color:rgb(209, 105, 20);
      padding: 20px;
      color: #000;
    }

    .footer {
      grid-column: 1 / 4;
      background-color: rgb(171, 164, 164);
      padding: 20px;
      color: #FFF;
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">HEADER</div>
    <div class="sidebar">SIDEBAR</div>
    <div class="main-content">MAIN CONTENT</div>
    <div class="footer">FOOTER</div>
  </div>
</body>
</html>

```
## OUTPUT
<img width="960" alt="image" src="https://github.com/Shavedha/Gridbox/assets/93427376/fa0719bd-ab76-4729-9003-1d059d1c8eb1">

## RESULT
Thus a web-layout using gridbox is implemented.
