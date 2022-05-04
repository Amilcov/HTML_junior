
   
<div id="id1" data-index="1" data-x="Eu sunt" data-cum="happy">


const elem = document.getElementById("wrapper");
const data = elem.dataset.index + " " + elem.dataset.cine + " " + elem.dataset.ce;
console.log('Datele stocate la nivel de element: ', data);
