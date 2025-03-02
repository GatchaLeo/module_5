<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        #wrapper {
            width: 100%;
        }

        header {
            background-color: #008833;
            padding: 1rem;
        }

        header h1 {
            color: #99ccff;
        }

        main {
            background-color: lightgrey;
            padding: 1rem;
            min-height: 50vh;
        }

        .large {
            font-size: 2em;
        }

        a {
            color: #0000ff;
            font-weight: bold;
        }

        footer {
            background-color: #008833;
            padding: 1rem;
            color: #99ccff;
            text-align: center;
        }
    </style>
</head>
<body>
    <div id="wrapper">
        <header>
            <h1>CSS inline to head</h1>
        </header>
        <main>
            <section>
                <p>
                    <strong class="large">Lorem</strong> dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                </p>
            </section>
            <section>
                <p>
                    <strong class="large">Ipsum</strong> sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, <a>Lorem ipsum</a> sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?
                </p>
            </section>
        </main>
        <footer>
            <p>copyleft 2025 J Neathawk</p>
        </footer>
    </div>
</body>
</html>
