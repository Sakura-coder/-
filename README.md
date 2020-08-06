<style>
    .container {
    min-block-size: 25ch;
    inline-size: 100%;
    max-inline-size: 720px;
    background: hsl(0 0% 90%);
    padding: 2rem;
    box-sizing: border-box;
    margin-inline: auto;
    }

    .flex {
    display: flex;
    flex-direction: column;
    }

    .grid {
    display: grid;
    }

    .place-items {
    place-items: center;
    }

    .place-content {
    place-content: center;
    }

    .align-items-and-content {
    align-items: center;
    justify-content: center;
    }

    h2, p {
    margin: 0;
    }

    body {
    display: grid;
    place-items: center;
    gap: 2rem;
    padding: 2rem;
    }
</style>
<body>
    <div class="place-items container flex">
        <h2>Flex</h2>
        <pre><code>place-items: center;</code></pre>
        <p>I'm just an example paragraph</p>
      </div>
      
      <div class="place-content container flex">
        <h2>Flex</h2>
        <pre><code>place-content: center;</code></pre>
        <p>I'm just an example paragraph</p>
      </div>
      
      <div class="align-items-and-content container flex">
        <h2>Flex</h2>
        <pre><code>
      align-items: center;
      justify-content: center;
      </code></pre>
        <p>I'm just an example paragraph</p>
      </div>
      
      <div class="place-items container grid">
        <h2>Grid</h2>
        <pre><code>place-items: center;</code></pre>
        <p>I'm just an example paragraph</p>
      </div>
      
      <div class="place-content container grid">
        <h2>Grid</h2>
        <pre><code>place-content: center;</code></pre>
        <p>I'm just an example paragraph</p>
      </div>
      
      <div class="align-items-and-content container grid">
        <h2>Grid</h2>
        <pre><code>
      align-items: center;
      justify-content: center;
      </code></pre>
        <p>I'm just an example paragraph</p>
      </div>
</body>
