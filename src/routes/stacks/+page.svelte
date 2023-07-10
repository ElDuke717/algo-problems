<nav>
    <a href="/">Home</a>
    <a href="/bst">Binary Search Trees</a>
    <a href="/ll">Linked Lists</a>
    <a href="/stacks">Stacks</a>
    <a href="/queues">Queues</a>
    <a href="/hash-tables">Hash Tables</a>
    <a href="/graphs">Graphs</a>
    <a href="/algorithms">Algorithms</a>
</nav>

<script>
    let stackSection1 = {
        title: "Introduction",
        content: [
            "Brief explanation of stacks",
            "Why it's important to understand them"
        ]
    };

    let stackSection2 = {
        title: "Fundamentals of Stacks",
        content: [
            "Explanation of key terms (Push, Pop, Top, isEmpty)",
            "A simple Stack example in JavaScript"
        ]
    };

    let stackSection3 = {
        title: "Conclusion",
        content: [
            "Recap of how stacks work with examples in JavaScript",
            "Importance and application of Stacks in JavaScript and in general programming",
            "Further resources for learning more about Stacks"
        ]
    };
</script>

<section>
    <h1>{stackSection1.title}</h1>
    <ul>
        {#each stackSection1.content as item (index)}
            <li>{item}</li>
        {/each}
    </ul>
</section>

<section>
    <h1>{stackSection2.title}</h1>
    <ul>
        {#each stackSection2.content as item (index)}
            <li>{item}</li>
        {/each}
    </ul>
</section>

<section>
    <h1>{stackSection3.title}</h1>
    <ul>
        {#each stackSection3.content as item (index)}
            <li>{item}</li>
        {/each}
    </ul>
</section>
