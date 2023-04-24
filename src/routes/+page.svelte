<script>
    let blogs = [
        {
            id: 1,
            title: 'my first blog',
            blogBody: 'This is my first blog.',
            datePosted: '4/24/2023'
        },
        {
            id: 2,
            title: 'my second blog',
            blogBody: 'This is my second blog.  I will keep writing things to fill up space.',
            datePosted: '4/24/2023'
        }
    ];
</script>

<div class="main-wrapper">
    <h1 class="main-header">Blog Posts</h1>
    <div class="blog-wrapper">
        {#each blogs as post (post.id)}
          <div class="blog-post-card">
            <h3>{post.title}</h3>
            <p>{post.datePosted}</p>
            <p>{post.blogBody}</p>
          </div>
        {/each}
    </div>
</div>


<style>
    .main-wrapper {
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }

    .main-header {
        text-align: center;
    }

    .blog-wrapper {
      width: 60vw;
      margin: 100px auto 0;
      display: flex;
      flex-direction: column;
    }

    .blog-post-card {
        background: rgb(207, 207, 207);
        margin: 10px;
        padding: 5px;
        border-radius: 10px;
    }
</style>
