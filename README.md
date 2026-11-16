# mid-term
Web client 
*.dll
temp/

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me | Christelle</title>

    <style>
        body {
            margin: 0;
            background-color: #101820;
            color: #e4e9ef;
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }

        header {
            background-color: #182a3a;
            border-bottom: 3px solid #ffd447;
            padding: 24px 16px;
            text-align: center;
        }

        h1 {
            margin: 0;
            color: #ffd447;
            text-transform: uppercase;
            letter-spacing: 3px;
        }

        main {
            max-width: 750px;
            margin: 24px auto;
            padding: 0 16px;
        }

        section {
            background-color: #182a3a;
            border: 1px solid #526779;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: #b8d5f0;
            border-bottom: 2px solid #ffd447;
            padding-bottom: 6px;
            margin-top: 0;
        }

        li::marker {
            color: #ffd447;
        }

        img {
            display: block;
            max-width: 100%;
            height: auto;
            margin: 16px auto 0;
            border-radius: 8px;
        }
    </style>
</head>

<body>
    <header>
        <h1>About Me</h1>
    </header>

    <main>
        <section>
            <h2>Introduction</h2>
            <p>
                Hi, I’m <strong>Christelle</strong>! I’m Armenian, and I’ve lived
                in Québec all my life. Welcome to my first webpage!
            </p>
        </section>

        <section>
            <h2>Languages</h2>
            <p>I speak three languages and I’m currently learning Spanish.</p>
            <ul>
                <li>French</li>
                <li>English</li>
                <li>Armenian</li>
                <li>Spanish (currently learning)</li>
            </ul>
        </section>

        <section>
            <h2>My Hobbies</h2>
            <ul>
                <li>Playing soccer</li>
                <li>Running</li>
                <li>Drawing and doing arts and crafts</li>
                <li>Cooking</li>
                <li>Gaming</li>
            </ul>

            <p>
                Soccer has had the biggest impact on me. I’ve been playing for
                years, and I’ve made many friends along the way. On the field,
                I’ve learned to trust my instincts, rely on my teammates, and
                encourage them through tough moments. I’m proud of how much
                soccer has helped me grow as both a player and a teammate.
            </p>

            <img src="soccer.jpg" alt="My soccer photo" width="480">
        </section>

        <section>
            <h2>My Education</h2>
            <ul>
                <li><strong>École Sourp Hagop</strong> — High school</li>
                <li><strong>Vanier College</strong> — Social Science</li>
                <li><strong>LaSalle College</strong> — Computer Science</li>
            </ul>
        </section>

        <section>
            <h2>My Favourite Movie</h2>
            <p>
                <em>X-Men</em> is my favourite movie because I’ve loved superheroes
                ever since I was a kid. I had fun reading the comics and
                imagining which superpower I’d choose. Seeing those characters
                come to life on screen made the movie even more exciting, and
                the actors made their emotions and struggles feel real.
            </p>

            <p>
                My favourite part of the story is how it makes me question whose
                side I’m on. I admire Professor X’s belief that humans and mutants
                can live together, but I also understand why Magneto has such a
                hard time trusting people after everything he’s been through.
                Every time I watch the movie, I wonder what I’d do in their place.
                That’s one of the reasons I keep coming back to it.
            </p>

            <img src="x-men-poster.jpg" alt="X-Men movie poster" width="260">
        </section>
    </main>
</body>
</html>
