<template>
  <nav class="px-6 py-2 flex justify-center w-full">
    <NuxtLink to="/" class="head text-red-700 text-3xl text-center w-full">
      Noob Santa Token
    </NuxtLink>
  </nav>

  <header class="bg-red-700 text-white">
    <main class="grid lg:grid-cols-2 place-content-center items-center max-w-7xl mx-auto p-6 gap-6">
      <img src="./public/01.jpg" alt="" class="w-full">
      <div class="">
        <h1 class="head text-7xl">Noob Santa Token ($Noob)</h1>
        <p class="mt-2">
          Noob Santa Token ($Noob) is a deflationary meme token on $BSC, created for fun and celebrations of Xmas season. <br> The aim is to enrich the binance ecosystem lovers through a valued Educational and Shopping 🛒 tokenization while we celebrate a joyful Xmas🎄🎁 together
        </p>
        <div class="flex gap-6 mt-6">
          <a href="https://x.com/NoobSantatoken?t=2EeX6yodqKUFpV6fmuDjJw&s=09" target="_blank" class="bg-white px-6 py-3 text-red-700 flex justify-center items-center gap-6 rounded-md w-fit hover:border-white border border-transparent hover:text-white hover:bg-transparent duration-500 ease-in-out">
            <Twitter class="w-6 h-6 " />
            Twitter / X
          </a>
          <a href="https://t.me/NoobSantaToken" target="_blank" class="bg-white px-6 py-3 text-red-700 flex justify-center items-center gap-6 rounded-md w-fit hover:border-white border border-transparent hover:text-white hover:bg-transparent duration-500 ease-in-out">
            <Telegram class="w-6 h-6 " />
            Telegram
          </a>
        </div>
      </div>
    </main>
  </header>

  <section class="bg-red-700 text-white">
    <img src="./public/snow.svg" class="w-full" alt="">
  </section>

  <section class="grid lg:grid-cols-2 max-w-7xl mx-auto mt-12 lg:divide-x lg:divide-y-0 divide-y divide-red-700 h-full">
    <div class="p-6">
      <h2 class="head text-red-700 text-5xl w-full capitalize text-center">Noob Santa Fundamentals</h2>
      <div class="mt-6">
        <li>NOOB SANTA FUNDAMENTALS        </li>
        <li>Ecommerce</li>
        <li>Santa pay (Crypto Debit card 💳/ wallet)        </li>
        <li>Santa Ai (Story telling, Riddles/Jokes, Gifts distribution, Customer relations)</li>
      </div>
    </div>
    <div class="place-content-center place-items-center w-full h-full p-6">
      <p>0x213e4b8ab51deB11b33a4dF1185437077395d402</p>
      <button class="py-3 px-6 rounded-md flex gap-4 text-white font-medium text-xl mt-4" :class="copied ? 'bg-green-600' : 'bg-red-700'" @click="copyAddress('0x213e4b8ab51deB11b33a4dF1185437077395d402')">
        <Copy class="w-7 h-7" />
        {{copy_text}}
      </button>
    </div>
  </section>

  <section class="max-w-7xl mx-auto px-6 py-20 gap-6">
    <h2 class="head text-red-700 text-5xl text-center w-full">Roadmap</h2>
    <div class="mt-12 flex lg:gap-6 lg:block relative"> 
      <div class="flex justify-center lg:justify-evenly lg:items-center relative w-full"> 
        <div class="flex flex-col lg:flex-row justify-around h-full lg:h-auto lg:w-full absolute">
          <h3 class="head bg-red-700 text-white p-2 text-3xl rounded-l-md lg:rounded-t-md lg:rounded-l-none">Phase 1</h3>
          <h3 class="head bg-red-700 text-white p-2 text-3xl rounded-l-md lg:rounded-t-md lg:rounded-l-none">Phase 2</h3>
          <h3 class="head bg-red-700 text-white p-2 text-3xl rounded-l-md lg:rounded-t-md lg:rounded-l-none">Phase 3</h3>
          <h3 class="head bg-red-700 text-white p-2 text-3xl rounded-l-md lg:rounded-t-md lg:rounded-l-none">Phase 4</h3>
        </div>
        <div class="bg-red-700 w-0.5 h-full lg:h-0.5 lg:w-full"></div>
      </div>

      <div class="grid lg:grid-cols-4 gap-6">
        <div class="border border-red-700 rounded-md p-2 mt-6" >
          <li>
            Community Building: Establish social media presence (Twitter, Reddit, Telegram etc).
          </li>
          <br>
          <li>
            Development: Develop the meme coin smart contract on Binance Smart Chain, Logo, Website etc.
          </li>
          <br>
          <li>
            Organic Marketing: Using Social media Ads, shillings and physical marketing strategies to attract real adopters for foundation building 
          </li>
        </div>
        <div class="border border-red-700 rounded-md p-2 mt-6" >
          <li>
            Listing on Decentralized Exchanges (DEXs): Get listed on PancakeSwap alongside Ads and Bsc trending 
          </li>
          <br>
          <li>
            Marketing Campaigns: Collaborate with influencers, Market makers and crypto enthusiasts.
          </li>
          <br>
          <li>
            Community Events: Host AMAs (Ask Me Anything), weekly shilling contests, and monthly giveaways. 
          </li>
        </div>
        <div class="border border-red-700 rounded-md p-2 mt-6" >
          <li>
            Partnerships and Collaborations: Partner with meme pages, content creators,KOLO, DIGIBUY, and lots more crypto project that we share same vision with.
          </li>
          <br>
          <li>
            NFT Integration: Introduce meme-themed NFTs (Non-Fungible Tokens)
          </li>
          <br>
          <li>
            Ecommerce/wallet Integration: Develop mobile and desktop wallets for seamless transactions in our ecommerce platform. 
          </li>
        </div>
        <div class="border border-red-700 rounded-md p-2 mt-6" >
          <li>
            Centralized Exchange (CEX) Listings: Get listed on reputable CEXs according to community votes.
          </li>
          <br>
          <li>
            Gaming and Entertainment: Integrate meme coin into gaming platforms or create exclusive content.
          </li>
          <br>
          <li>
            Charity Initiatives: Donate to meme-related charities or community-chosen causes. 
          </li>
        </div>
      </div>
    </div>
  </section>

  <section class="bg-red-700 text-white">
    <main class="grid lg:grid-cols-2 place-content-center items-center max-w-7xl mx-auto p-6 gap-6 mt-12">
      <img src="./public/04.jpg" alt="" class="w-full">
      <div>
        <h2 class="head text-5xl w-full">Long-Term Goals (2025+)</h2>
        <div class="mt-6 list-disc block">
          <li>
            Meme Ecosystem: Develop a comprehensive meme ecosystem with various applications.
          </li>
          <li>
            Decentralized Governance: Implement decentralized governance for community-driven decision-making.
          </li>
          <li>
            Mainstream Adoption: Expand meme coin usage beyond the crypto community.
          </li>
        </div>
      </div>

    </main>
  </section>

  <section class="px-6 gap-6">
    <main class="grid lg:grid-cols-2 place-content-center items-center max-w-7xl mx-auto p-6 gap-6 mt-12">
      <img src="./public/02.jpg" alt="" class="w-full">
      <div>
        <h2 class="head text-red-700 text-5xl w-full">TOKENOMICS </h2>
        <div class="mt-6 list-disc block">
          <li>
            Marketing 10%
          </li>
          <li>
            Exchange listings 5%
          </li>
          <li>
            Team and Advisors 5%
          </li>
          <li>
            Utility building 5%
          </li>
          <li>
            Liquidiy 75%
          </li>
        </div>
      </div>

    </main>
  </section>

  <section class="">
    <main class="grid lg:grid-cols-2 place-content-center items-center max-w-7xl mx-auto p-6 gap-6 mt-12">
      <div>
        <h2 class="head text-red-700 text-5xl w-full">Technical Development Roadmap</h2>
        <div class="mt-6 list-disc block">
          <li>
            Smart Contract Audit: Conduct regular security audits.
          </li>
          <li>
            New Innovation: open to new ideas of what to build for sustainable growth.
          </li>
        </div>
        <h2 class="head text-red-700 text-5xl w-full mt-12">Community Engagement Roadmap        </h2>
        <div class="mt-6 list-disc block">
          <li>
            Community Contests: Regularly host contests, quizzes, and giveaways.
          </li>
          <li>
            Meme Creation Incentives: Reward creators for producing engaging meme content.
          </li>
          <li>
            Community Governance: Establish community-driven decision-making processes.
          </li>
        </div>
      </div>
      <img src="./public/03.jpg" alt="" class="w-full">
    </main>
  </section>

  <footer class="p-6 bg-red-700">
    <p class="text-center text-white">&copy; Noob Santa Token {{ new Date().getFullYear() }}</p>
    <div class="flex justify-center gap-6 mt-2">
      <a href="https://x.com/NoobSantatoken?t=2EeX6yodqKUFpV6fmuDjJw&s=09" target="_blank" class="bg-white px-6 py-3 text-red-700 flex justify-center items-center gap-6 rounded-md w-fit hover:border-white border border-transparent hover:text-white hover:bg-transparent duration-500 ease-in-out">
            <Twitter class="w-6 h-6 " />
            Twitter / X
          </a>
          <a href="https://t.me/NoobSantaToken" target="_blank" class="bg-white px-6 py-3 text-red-700 flex justify-center items-center gap-6 rounded-md w-fit hover:border-white border border-transparent hover:text-white hover:bg-transparent duration-500 ease-in-out">
            <Telegram class="w-6 h-6 " />
            Telegram
          </a>
    </div>
  </footer>
</template>
<script setup>
import { toast } from 'vue3-toastify';
import 'vue3-toastify/dist/index.css';
import { ref } from "vue";

let copy_text = 'Copy Contract Address';
let copied = ref(false);

const copyAddress = (text) => {
    // Use the Clipboard API if available
    if (navigator.clipboard && window.isSecureContext) {
    navigator.clipboard.writeText(text);
    toast.success("Contact Address copied to clipboard", {
      autoClose: 1000,
      position: toast.POSITION.TOP_CENTER,
      theme: toast.THEME.COLORED
    });
    
    copy_text = 'Copied';    
    copied.value = true
  } 
  // Fallback method for older browsers
  else {
    // Create a temporary textarea element
    const textArea = document.createElement('textarea');
    textArea.value = text;
    
    // Make the textarea out of viewport
    textArea.style.position = 'fixed';
    textArea.style.left = '-999999px';
    textArea.style.top = '-999999px';
    document.body.appendChild(textArea);
    
    // Select the text
    textArea.focus();
    textArea.select();
    
    // Copy the text
    let successful = false;
    try {
      successful = document.execCommand('copy');
    } catch (err) {
      console.error('Unable to copy text', err);
    }
    
    // Remove the temporary textarea
    document.body.removeChild(textArea);
    
    // return successful;
    toast.success("Contact Address copied to clipboard", {
        autoClose: 1000,
        position: toast.POSITION.TOP_CENTER,
        theme: toast.THEME.COLORED
    });
    copy_text = 'copied';
    copied = true
  }    

  // Fallback method for older browsers
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Shadows+Into+Light&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

.head{
  font-family: "Shadows Into Light", cursive;
  font-weight: 600;
  font-style: normal;
}

* {
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
</style>