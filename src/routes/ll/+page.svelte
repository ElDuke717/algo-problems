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


<style>
    /* Your CSS styles here */
</style>

<h1>Linked Lists</h1>

<script>
    let section1 = {
        title: "Introduction",
        content: [
            "Brief explanation of linked lists",
            "Why it's important to understand them"
        ]
    };

    let section2 = {
        title: "Fundamentals of Linked Lists",
        content: [
            "Explanation of key terms (Node, Link)",
            "Differences between Array and Linked List",
            "A simple Linked List example in JavaScript"
        ]
    };

    let section3 = {
        title: "Linked List Operations",
        content: [
            "Insertion",
            "Deletion",
            "Searching",
            "JavaScript code examples for each operation"
        ]
    };

    let section4 = {
        title: "Types of Linked Lists",
        content: [
            "Singly Linked Lists",
            "Doubly Linked Lists",
            "Circular Linked Lists",
            "JavaScript code examples for each type"
        ]
    };

    let section5 = {
        title: "Conclusion",
        content: [
            "Recap of how linked lists work with examples in JavaScript",
            "Importance and application of Linked Lists in JavaScript and in general programming",
            "Further resources for learning more about Linked Lists"
        ]
    };
</script>

<section>
    <h1>{section1.title}</h1>
    <ul>
        {#each section1.content as item (index)}
            <li>{item}</li>
        {/each}
    </ul>
</section>

<section>
    <h1>{section2.title}</h1>
    <ul>
        {#each section2.content as item (index)}
            <li>{item}</li>
        {/each}
    </ul>
</section>

<section>
    <h1>{section3.title}</h1>
    <ul>
        {#each section3.content as item (index)}
            <li>{item}</li>
        {/each}
    </ul>
</section>

<section>
    <h1>{section4.title}</h1>
    <ul>
        {#each section4.content as item (index)}
            <li>{item}</li>
        {/each}
    </ul>
</section>

<section>
    <h1>{section5.title}</h1>
    <ul>
        {#each section5.content as item (index)}
            <li>{item}</li>
        {/each}
    </ul>
</section>
