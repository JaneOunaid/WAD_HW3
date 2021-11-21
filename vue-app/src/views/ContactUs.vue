<template>
  <div class="contacus">
    <h1>Contacts</h1>
    <div v-for="contact in contacts" :key="contact.phone" :email=contact.email>
      <p>
        Tel: {{contact.phone}} <br> Email: {{contact.email}}
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "contactus",
  data(){
    return{
      contacts:[
        {phone: "+327 999 8888", email: "support@postit.com"},
        {phone: "+327 999 7777", email: "marketing@postit.com"},
      ]
    }
  }
}
</script>
