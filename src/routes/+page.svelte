<script lang="ts">

const url = "https://nuxt-test-lovat-three.vercel.app/";

	let title = "Default Title";
	let description = "Default description";
	let imageUrl =
	  "https://images.pexels.com/photos/24516444/pexels-photo-24516444/free-photo-of-a-plate-of-food-with-a-candle-and-flowers.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1";
  </script>
  
  <svelte:head>
	<title>{title}</title>
	<meta name="description" content={description} />
	<meta property="og:type" content="article" />
	<meta property="og:title" content={title} />
	<meta property="og:description" content={description} />
	<meta property="og:image" content={imageUrl} />
	<meta
	  property="og:url"
	  content="https://www.tiwarnews.net/ckb/newsDetail/71"
	/>
  </svelte:head>
  
  <section>hi</section>
  <!-- social media icons -->
  <div class="flex gap-1 mt-2 lg:mt-0">
	
	<a href={`https://www.facebook.com/sharer/sharer.php?u=${url}text=${title}`} target="_blank" rel="noopener noreferrer">
	  Facebook
	</a>
	
  </div>