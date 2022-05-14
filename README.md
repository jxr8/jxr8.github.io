## Joshua Robinson
<style>

.accordion {
  max-width: 500px;
  border: 1px solid #000;
  border-bottom: none;
}

.accordion:last-child {
  border-bottom: 1px solid #000;
}

.accordion-header {
  display: flex;
  padding: 16px;
  cursor: pointer;
  background-color: #F2F2F2;
}

.accordion-title {
  flex: 1;
}

.accordion-icon: {
  width: 16px;
}

.accordion-content {
  padding: 16px;
}

.accordion-content {
  display: none;
}

</style>


<a href="https://github.com/jxr8/jxr8.github.io">Joshua Robinson GitHub</a>

<a href="file:///Users/joshuarobinson/Desktop/JavaScript/CSIT281-JavaScript/exam.html">Grocery List Project</a>
<a href="file:///Users/joshuarobinson/Desktop/JavaScript/CSIT281-JavaScript/sports.html">Sports Project</a>


<section id="education">

<h2>Education</h2>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Gar-Field Senior High School</div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">

        I graduated in 2020 with an advanced studies diploma. I was also an
        Interantional Baccalaureate Career Related diploma recipient.




    </div>
</div>


<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Mount Aloysius College</div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
      I will earn my bachelors degree in Information Technology with a concentration
      in Cyber Security in 2024. I am also planning to earn my MBA in 2025 in the 4+1
      program Mount Aloysius offers.
    </div>
</div>




</section>

<script>

const accordionHeaders = document.getElementsByClassName('accordion-header');
const accordionContents = document.getElementsByClassName('accordion-content');
const accordionIcons = document.getElementsByClassName('accordion-icon');

for (let i = 0; i < accordionHeaders.length; i++) {
  accordionHeaders[i].addEventListener('click', () => {
    accordionContents[i].style.display = accordionContents[i].style.display == 'block' ? 'none' : 'block';
    accordionIcons[i].innerHTML = accordionContents[i].style.display == 'block' ? '-' : '+';
  });
}

  

  
</script>
