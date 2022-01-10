<template>
  <section id="contatti">
      <div class="container">
          <h2>Contatti</h2>
            <form action="">
                <div class="row">
                    <div class="col-6 mb-3">
                        <label for="nome">Nome</label>
                        <input id="nome" class="form-control" type="text" placeholder="Nome">
                    </div>
                    <div class="col-6 mb-3">
                        <label for="cognome">Cognome</label>
                        <input id="cognome" class="form-control" type="text" placeholder="Cognome">
                    </div>
                    <div class="col-6 mb-3">
                        <label for="email">Email</label>
                        <input id="email" class="form-control" type="email" placeholder="Email">
                    </div>
                    <div class="col-6 mb-3">
                        <label for="tel">Telefono</label>
                        <input id="tel" class="form-control" type="phone" placeholder="Tel">
                    </div>
                    <div class="col-12 mb-3">
                        <label for="messaggio">Messaggio</label>
                        <textarea class="form-control" id="messaggio" cols="30" rows="10" placeholder="Inserisci il messaggio..."></textarea>
                    </div>
                    <div class="col-12 text-center">
                        <button class="btn btn-lg btn-primary">Invia</button>
                    </div>
                </div>
            </form>
      </div>
  </section>
</template>

<script>
export default {
    name: 'Contact'
}
</script>

<style>

</style>