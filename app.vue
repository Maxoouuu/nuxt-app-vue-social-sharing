<template>
  <div>
    
    <ShareNetwork network="facebook" url="https://news.vuejs.org/issues/180"
      title="Say hi to Vite! A brand new, extremely fast development setup for Vue."
      description="This week, I’d like to introduce you to 'Vite', which means 'Fast'. It’s a brand new development setup created by Evan You."
      quote="The hot reload is so fast it\'s near instant. - Evan You" hashtags="vuejs,vite">
      Share on Facebook
    </ShareNetwork>
    
  </div>
</template>

<script>
import Vue from 'vue';
import VueSocialSharing from 'vue-social-sharing';

// Initialize VueSocialSharing and set custom sharing networks if specified
Vue.use(VueSocialSharing, [ serialize(options)][0]);
</script>