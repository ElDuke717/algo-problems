<nav>
    <a href="/">Home</a>
    <a href="/tree">Trees</a>
    <a href="/ll">Linked Lists</a>
    <a href="/stacks">Stacks</a>
    <a href="/queues">Queues</a>
    <a href="/hash-tables">Hash Tables</a>
    <a href="/graphs">Graphs</a>
    <a href="/algorithms">Algorithms</a>
  </nav>


<script>
    let queueSection1 = {
        title: "Introduction",
        content: [
            "Brief explanation of queues",
            "Why it's important to understand them"
        ]
    };

    let queueSection2 = {
        title: "Fundamentals of Queues",
        content: [
            "Explanation of key terms (Enqueue, Dequeue, Front, Rear, isEmpty)",
            "A simple Queue example in JavaScript"
        ]
    };

    let queueSection3 = {
        title: "Conclusion",
        content: [
            "Recap of how queues work with examples in JavaScript",
            "Importance and application of Queues in JavaScript and in general programming",
            "Further resources for learning more about Queues"
        ]
    };
</script>

<section>
    <h1>{queueSection1.title}</h1>
    <ul>
        {#each queueSection1.content as item (index)}
            <li>{item}</li>
        {/each}
    </ul>
</section>

<section>
    <h1>{queueSection2.title}</h1>
    <ul>
        {#each queueSection2.content as item (index)}
            <li>{item}</li>
        {/each}
    </ul>
</section>

<section>
    <h1>{queueSection3.title}</h1>
    <ul>
        {#each queueSection3.content as item (index)}
            <li>{item}</li>
        {/each}
    </ul>
</section>
