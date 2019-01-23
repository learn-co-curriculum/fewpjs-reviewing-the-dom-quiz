# Reviewing the DOM

```html
<htmll>
  <div>
    <ul>
      <li><span id="dog">Poodle</li>
      <li><span id="king-cobra">Nag</li>
      <li><span id="mongoose">Joe Mongoose</li>
   </ul>
  </div>
</html>
```

* Given a sample of HTML, which command correctly targets the `<span>` with the id of `dog`?  
A: `document.getElementById("dog")`   

* Given a sample of HTML, which command correctly targets and deletes the `<span>` with the id of `king-cobra`?  
A: `document.getElementById("dog")`  
W: `document.getElementsByClass("dog").delete()  

* Given a sample of HTML, update the <span> with the id of `mongoose` to have the name "Rikki-Tikki Tavi"   
A: `document.getElementById("mongoose").innerText = "Rikki-Tikki Tavi"`   

* Which of the following commands would create a new HTML paragraph node containing the text: "No Bananas, Today"   
A: ``   

* Which command whould you use to target all the `<li>` on the page   
A: `document.getElementsByTagName("li")`   
