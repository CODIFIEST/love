<script lang="ts">
  async function connectMetaMask() {
    console.log('wallet button clicked')

  }
 </script>

<main>

<div class="hero min-h-screen bg-base-200">
  <div class="hero-content text-center">
    <div class="max-w-md">
      <h1 class="text-5xl font-bold">I LOVE</h1>
      <p class="py-6">Claim your personal love ens here.
        <br> Buy with LOVE.
        <br> Share your LOVE ens.</p>
        <label for="my-modal" class="btn">Connect Wallet</label>
      <!-- <button on:click={connectMetaMask} class="btn btn-primary">Connect Wallet</button> -->
    </div>
  </div>
</div>

</main>
<input type="checkbox" id="my-modal" class="modal-toggle" />
<div class="modal">
  <div class="modal-box">
    <div style="width:100%;height:0;padding-bottom:85%;position:relative;"><iframe src="https://giphy.com/embed/g7GKcSzwQfugw" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div>
    <!-- <h3 class="font-bold text-lg">Congratulations random Internet user!</h3>
    <p class="py-4">You've been selected for a chance to get one year of subscription to use Wikipedia for free!</p>
  -->
  <div class="modal-action">
    <label for="my-modal" class="btn">Yay!</label>
  </div> 
  </div>
</div>

<style>
</style>