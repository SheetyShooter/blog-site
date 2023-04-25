<div class="signin-wrapper">
    <div class="signin-card">
        <h1 class="signin-header">Sign In</h1>
        <hr>
        <input class="singin-input" type="email" placeholder="Email">
        <input class="singin-input" type="password" placeholder="Password">
        <div class="singin-checkbox">
            <label for="keepSignedIn">Keep you signed in?</label>
            <input type="checkbox" name="keepSignedIn">
        </div>
        <div class="signin-button-wrapper">
            <button class="signin-button">Sign In</button>
            <button class="signin-button">Sign Up</button>
        </div>
    </div>
</div>


<style>
    .signin-wrapper {
        color: #fff;
        background: linear-gradient(to top right, rgb(45, 203, 214), rgb(37, 155, 163));
        height: 98vh;
        padding-top: 150px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }

    .signin-card {
        background: rgba(255, 255, 255, 0.19);
        backdrop-filter: blur(5px);
        -webkit-backdrop-filter: blur(5px);
        width: 25vw;
        min-width: 300px;
        margin: auto;
        padding-bottom: 30px;
        display: flex;
        flex-direction: column;
        align-items: center;
        border-radius: 10px;
        box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
    }

    .signin-card h1 {
        font-weight: 100;
        margin-bottom: 0;
    }

    .signin-card hr {
        background: #fff;
        width: 40%;
        height: 4px;
        border: none;
        border-radius: 3px;
    }

    .singin-input {
        height: 20px;
        width: 40%;
        margin-top: 8px;
        padding: 5px;
        border: none;
        border-radius: 5px;
    }

    .singin-checkbox {
        margin-top: 20px;
        font-weight: 100;
    }

    .signin-button-wrapper {
        width: 60%;
        margin-top: 15%;
        display: flex;
        flex-direction: column;
    }

    .signin-button {
        color: #fff;
        background: rgb(83, 177, 83);
        width: 100%;
        height: 30px;
        margin-bottom: 5px;
        border: none;
        border-radius: 10px;
    }
</style>