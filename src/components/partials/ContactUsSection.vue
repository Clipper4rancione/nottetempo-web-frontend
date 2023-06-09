<script>
    export default {
        name: 'ContacUsSection'
    }
</script>

<template>
    <section class="contact_us_section py-5">
    <div class="container">
        <h2 class="text-center py-5">CONTATTACI</h2>
        <form action="#" class="row">
            <div class="col-6">
                <label for="inputName" class="form-label">Nome</label>
                <input type="text" id="inputName" class="form-control c-form" placeholder="Inserisci qui il tuo nome">
            </div> 
            <div class="col-6">
                <label for="inputMail" class="form-label">Email</label>
                <input type="email" id="inputMail" class="form-control c-form" placeholder="Inserisci qui il tuo indirizzo e-mail">
            </div>
            <div class="col-12">
                <textarea name="" id="messageArea" class="form-control c-form my-4" rows="6" placeholder="Scrivi qui il tuo messaggio..."></textarea>
            </div>
            <div class="col-12 d-flex justify-content-center">
                <button type="submit" class="btn btn-warning col-3">
                    Invia
                </button>
            </div>
        </form>
    </div>
    </section>
    
</template>



<style lang="scss" scoped>
.contact_us_section{
    background: rgb(42,42,42);
    background: linear-gradient(180deg, rgba(42,42,42,1) 0%, rgba(91,91,91,1) 100%); 

    .form-control{
        background: transparent;
        border-radius: 0px;
    }
    .form-control:focus{
        box-shadow: inset 0 2px 2px rgba(0, 0, 0, 0.075), 0 0 8px #f3e00c;
    }
}
</style>