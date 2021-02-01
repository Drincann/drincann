### Hi there 👋

<!--
**drinkal/drinkal** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<span id="star"></span>

<script src="https://cdn.bootcdn.net/ajax/libs/axios/0.21.1/axios.min.js"></script>
<script>
(async () => {
    const data = await axios.get('https://api.github.com/users/drinkal/repos');
    let star = 0;
    data.forEach((val)=>{
        star += val.stargazers_count;
        document.querySelector('#star').innerHTML = star;
    });
    
})()
</script>
