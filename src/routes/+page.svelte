<script>
  import Counter from './Counter.svelte';
</script>


<section>
  <h1>
    Download More Ram
  </h1>

  <table border="0">
    <tr>
      <td>
        <Counter />
      </td>
      <td>
        GB
      </td>
    </tr>
  </table>

  <button>Start!</button>
</section>

<style>
  section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex: 0.6;
  }

  h1 {
    width: 100%;
  }

  button {
    margin-top: 20px;
    padding: 16px 32px;
    border-radius: 0;
    border: 1px solid #ccc;
    color: #fff;
    background-color: #bd4f14;
    font-size: 1.2rem;
    cursor: pointer;
  }
</style>
