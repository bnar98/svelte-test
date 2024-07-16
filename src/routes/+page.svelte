<script lang="ts">

const url = "https://svelte-test-one-navy.vercel.app/";

	let title = "Default Title";
	let description = "Default description";
	let imageUrl ="https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885_960_720.jpg";</script>
  
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