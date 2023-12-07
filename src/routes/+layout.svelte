<script>
  import "../app.css";
</script>

<style>
  /* Set your desired background color */
  :global(body) {
    background-color: #3498db; /* Replace with your preferred color code */
    margin: 0; /* Reset default body margin */
    box-shadow: inset 0 0 10px rgba(255, 255, 255, 0.2);
    font-family: 'Arial', sans-serif; /* Optional: Set a default font-family */
  }
    /* Center the app header */
  .app-header {
    background-color: #4682b4; /* Adjust the background color as needed */
  }
</style>
  <div class="text-center p-4 bg-gray-700 text-white app-header">
    <h1 class="text-3xl font-bold">Asma-ul-Husna</h1>
    <h2 class="text-xl font-bold">The 99 names and attributes of Allah (S.W.T)</h2>
    <!-- Add additional header content as needed -->
  </div>


<slot/>


<slot/>
