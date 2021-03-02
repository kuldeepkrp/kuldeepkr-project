# kuldeepkr-project

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My tribute page</title>
</head>

<style>
  body {
       margin: auto;
       padding: auto;
       background-color: lightgray;

  }
   h1 {
      text-align: center;
      color: red; 

   }

   #tribute-info {
      text-align: center;
      color: blue;
      text-decoration: underline;

   }

   img {
    display: block;
    margin-left: auto;
    margin-right: auto;
   }
  
  #image {
    width: 100%;
    height: auto;
    max-width: 625px;
    margin-left: auto;
    margin-right: auto;
    display: block;
  }

   #image-label {
    text-align: center;

   }

   #main-content h2 {
    text-align: center;
    text-decoration: underline;

   }

   iframe {
    display: block;
    margin-left: auto;
    margin-right: auto;

   }



</style>


<body id='main'>
  
  <header>
    <section id="title">
      <h1><u>Srinivasa Ramanujan</u></h1>
      <h2 id="tribute-info">The Man Who Knew Infinity</h2>
      <div id="img-div">
        <img id="image" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR6PmXa4ptHdYjkxzcmKXzPgRZaXgpviczhHg&usqp=CAU" alt="Srinivasa Ramanujan" width="50%">
        <p id="img-caption"><em>
        In this Indian name, the name <strong>Srinivasa</strong> is a <strong>Patronymic</strong>, and the person should be referred to by the given name, <strong>Ramanujan</strong>.
     </em></p><hr/>
      </div>
    </section>
  </header>
  
  <main>
    <div id="main-content">
      <article class="container-1">
        <h2>Here's a time line of S. Ramanujan's life:</h2>
        <ul id="time-line-list" class="text-content">
          <li><strong><u>22 December </strong><time datetime="1887"><strong>1887</u></strong></time> - Born in Erode, Madras Presidency, British India</li></br>

          <li><time datetime="1902"><strong><u>1902</u></strong></time> - Ramanujan was shown how to solve cubic equations and he developed his own method to solve the quartic. The following year he tried to solve the quintic, not knowing that it could not be solved by radicals.</li></br>

          <li><time datetime="1903"><strong><u>1903</u></strong></time> - When he was 16, Ramanujan obtained from a friend a library copy of <em> A Synopsis of Elementary Results in Pure and Applied Mathematics</em>, G. S. Carr's collection of 5,000 theorems.</li></br>

          <li><time datetime="1909"><strong><u>1909</u></strong></time> - Ramanujan married Janaki, a girl his mother had selected for him a year earlier and who was ten years old when they married.</li></br>

          <li><time datetime="1911"><strong><u>1911</u></strong></time> - In his 17-page paper "Some Properties of Bernoulli's Numbers", Ramanujan gave three proofs, two corollaries and three conjectures.</li></br>

          <li><time datetime="1916"><strong><u>1916</u></strong></time> - In March,Ramanujan was awarded a Bachelor of Arts by Research degree (the predecessor of the PhD degree) for his work on highly composite numbers, sections of the first part of which had been published the preceding year in the <em>Proceedings of the London Mathematical Society.</em></li></br>

          <li><strong><u>2 May </u></strong><time datetime="1918"><strong><u>1918</u></strong></time> -  Ramanujan was elected a <em>Fellow of the Royal Society</em>, one of the youngest and second Indian admitted, after <strong><u>Ardaseer Cursetjee</u></strong> in <strong><u>1841</u></strong>. </li></br>

          <li>On <strong><u>13 October </u></strong><time datetime="1918"><strong><u>1918</u></strong></time>  Ramanujan was the first Indian to be elected a Fellow of Trinity College, Cambridge.</li></br>

          <li><time datetime="1920"></time><strong><u>1920</u></strong></time> - Ramanujan was died at the age of <strong>32</strong></li></br>
          
        </ul> 
      </article>
      <hr/>
      <article id="achievement" class="text-content">
         <p><em> Ramanujan has been described as a person of a somewhat shy and quiet disposition, a dignified man with pleasant manners. He achieved many things in very young age. Here are some achievement by S. Ramanujan:</em></p>
         <iframe src = " Ramanujan.pdf" style="width:500px; height:300px;"></iframe>
      </article>
      <hr/>

      <article id="tribute" class="text-content">
          <p><em><strong> On 22 December 2012</strong>, the former Prime Minister of India, <strong>Dr Manmohan Singh</strong>, paid tribute to <strong>Srinivasa Ramanujan</strong> on the occasion of his <strong>125th</strong> Birth Anniversary in Chennai and declared <strong>December 22</strong> as <strong>National Mathematics Day</strong>.</em></p>
        
      </article>
      <hr/>

    </div>
  </main>
  
  <footer>
    <div id="footer-content">
      <secion> If you have time, you should read more about this incredible human being on his <a href="https://en.wikipedia.org/wiki/Srinivasa_Ramanujan" id="tribute-link" target="_blank">Wikipedia entry</a>.
      </section>
    </div>
  </footer>
</body>
