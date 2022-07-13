<html lang="en">

    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">

        <title>To do list</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet"
            integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

        <link rel="stylesheet" href="tstyle.css">

    </head>

    <body>


        <main>
            <div class=" container rounded-3 border border-2 border-dark my-5 bg-white" style="height:auto;">
                <div>
                    <h1 class=" h1">To Do List</h1>
                    <div class="row">
                        <div class=" col-8">
                            <input class=" py-3 form-control shadow" placeholder="Enter your task" type="text"
                                id="inputText">
                        </div>
                        <div class="col-2">
                            <button onclick="addList()" class=" mt-2 btn btn-dark"> Add </button>
                        </div>
                    </div>
                </div>
                <hr>
                <div class="row rounded bg-white">
                    <div class=" col-12">
                        <ul class=" list-group" id="list"></ul>
                    </div>
                </div>

            </div>
        </main>



        <script src="j.js"></script>
    </body>

</html>
