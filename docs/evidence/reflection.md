
**Abracadabra Reflection**

**1. What happens when you open index.html directly in the browser (file://) vs using the development server?**
        Opening the file directly in the browser displays the boring ACME website with the explaination 
        "😴 Something's missing...
        This webpage needs to be served by a development server to show its true potential. Try using npm to serve it properly!"

        Using a development server, the boring ACME webside will show with the explaination
        "🤔 Close, but not quite right...
        You're using a development server, but the magic is tuned for port 3000. Try "npm run serve"!

**2. Why does the magic only work on port 3000 specifically?**
        The magic only works on port 3000 because JavaScript checks what port the server is being run on, and will only run that specific code if it is on port 3000.

**3. What did you learn about npm scripts and how they can chain together?**
        I learned that npm scripts allow you to run complex commands easily with shortcuts and they chain together in various ways such as sequentially, simultaneously, and enviromentally.

**4. How does this project demonstrate the value of development tools and automation?**
        This project demonstrates the value of development tools and automation by showing the various downsides of not using it, such as the lack of organization, repetitive tasks effecting time-efficieny, and wasting resouces. It shows how much easier development is when using these tools, especially with npm scripts.

**5. What other npm scripts could be useful for web development workflows?**
        One npm script that can be useful for web development workflows is making mass testing various changes easier, instead of having to use more extensive testing methods.