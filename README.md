<svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
  <rect width="100" height="100" fill="lightgray"/>
  <circle cx="50" cy="50" r="30" fill="blue" id="interactive-circle"/>
  <script>
    document.getElementById('interactive-circle').addEventListener('click', () => {
      alert('You clicked the circle!');
    });
  </script>
</svg>
