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
        "Explanation of key terms (Push, Pop, Top, isEmpty, Peek)",
      ],
      code: `class Node {
        constructor(val) {
          this.val = val;
          this.next = null;
        }
      }
  
      class Stack {
        constructor(node) {
          this.top = node;
        }
  
        push(node) {
          node.next = this.top;
          this.top = node;
        }
  
        pop() {
          if (this.top === null) {
            return null;
          }
          let node = this.top;
          this.top = this.top.next;
          node.next = null; // Clear the reference to next
          return node;
        }
  
        peek() {
          return this.top;
        }
      }
      
  // A node is added to the top of the stack when it is constructed
  let stack = new Stack(a);
  console.log(stack);
  
  // Add more nodes to the stack with the push method.
  stack.push(b);
  stack.push(c);
  
  console.log(stack.peek()); // Node { val: 'c', next: Node { val: 'b', next: Node { val: 'a', next: null } } }
  
  let popped = stack.pop();
  console.log(popped); // Node { val: 'c', next: null }
  
  console.log(stack.peek()); // Node { val: 'b', next: Node { val: 'a', next: null } }`
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
    <h2>JavaScript Stack Implementation Example</h2>
    <pre>{stackSection2.code}</pre>
  </section>
  
  <section>
    <h1>{stackSection3.title}</h1>
    <ul>
      {#each stackSection3.content as item (index)}
        <li>{item}</li>
      {/each}
    </ul>
  </section>
  
