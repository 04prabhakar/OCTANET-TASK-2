# OCTANET-TASK-2
# OCTANET-TASK-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="theme-color" content="#062e3f">
    <meta name="Description" content="A dynamic and aesthetic To-Do List WebApp.">

    <!-- Google Font: Italics -->
    
    <!-- font awesome (https://fontawesome.com) for basic icons; source: https://cdnjs.com/libraries/font-awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.0-2/css/all.min.css" integrity="sha256-46r060N2LrChLLb5zowXQ72/iKKNiw/lAmygmHExk/o=" crossorigin="anonymous" />

    <link rel="shortcut icon" type="image/png" href="assets/favicon.png"/>
    <link rel="stylesheet" href="CSS/main.css">
    <link rel="stylesheet" href="CSS/corner.css">
    <title>ToDoList</title>

</head>

<body>
    <div id = "header">
        <div class="flexrow-container">
            <div class="standard-theme theme-selector"></div>
            <div class="light-theme theme-selector"></div>
            <div class="darker-theme theme-selector"></div>
        </div>
        <h1 id="title">To Do List<div id="border"></div></h1>
    </div>

  <div id="form">
        <form>
            <input class="todo-input" type="text" placeholder="Add a task.">
            <button class="todo-btn" type="submit">Add</button>
        </form>
    </div>        
    <div>
        <p><span id="datetime"></span></p>
        <script src="JS/time.js"></script>
    </div>

  <div id="myUnOrdList">
        <ul class="todo-list">
        </ul>
    </div>
    <script src="JS/main.js" type="text/javascript"> </script>
</body>
</html>
