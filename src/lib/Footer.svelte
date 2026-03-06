<script>
    import img from '$lib/assets/crossfit.jpg';
	import { formatPostcssSourceMap } from 'vite';
</script>

<footer class="footer">
    <div class="footer__wrapper wrap">
        <div class="footer__img">
            <img src="{img}" alt="">
        </div>
        <div class="footer__info">
            <h2>venha fazer seu <br>primeiro treino gratis</h2>
            <p>bla bla bla bla venha ca participar</p>
            <div class="footer__btns">
                <a href="http://api.whatsapp.com/send?phone=5514999032024" class="btn"> Whatsapp</a>
                <a href="mailto:matheusmpmenezes@gmail.com" class="btn"> E-mail</a>
            </div>
        </div>

        
    </div>

    
</footer>

<style>
    .footer{
        margin-top: 90px ;
    }
    .footer__wrapper{
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 20px;
        align-items: center;
    }
    .footer__img{
        position: relative;
    }
    .footer__img::after{
        content: '';
        position: absolute;
        inset: 0;
        background-color: var(--overlay);
    }
    img{
        border-radius: 16px;
    }
    p{
        margin-top: 16px;
        max-width: 360px;
    }
    h2{
        font-size: calc(36/16 * 1rem);
    }
    .footer__btns{
        margin-top: 24px;
        display: flex;
        gap: 8px;
    }

    
    

</style>