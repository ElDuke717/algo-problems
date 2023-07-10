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
    let section1 = {
        title: "Introduction",
        content: [
            "Brief explanation of binary search trees",
            "Why it's important to understand them"
        ]
    };

    let section2 = {
        title: "Fundamentals of Binary Search Trees",
        content: [
            "Explanation of key terms (Node, Edge, Root, Parent, Child, Sibling, Leaf)",
            "The property of Binary Search Trees",
            "A simple BST example in JavaScript"
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


  
    
   