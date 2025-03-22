<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'

const openReadmeInEditor = () => fetch('/__open-in-editor?file=README.md')
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>When</template>

    (Almost) Every Sunday and Saturday we hold <b>all day mindfulness retreats</b>.
    <br>
    Saturday :
    <ul>
      <li>Start 8:00 AM PST → 11:00 AM EST</li>
      <li>5:55 PM PST → 8:55 PM EST</li>
    </ul>
    <br>
    Sunday :  
    <ul>
      <li>Start 10:00 AM PST → 1:00 PM EST Ends</li>
      <li>5:55 PM PST → 8:55 PM EST</li>
    </ul>
    <!-- <a href="https://vuejs.org/" target="_blank" rel="noopener">official documentation</a>
    provides you with all information you need to get started. -->
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Where?</template>

    We host this on Zoom.
    <br>
    Link: <a href="https://us06web.zoom.us/j/5620489534" target="_blank" rel="noopener">https://us06web.zoom.us/j/5620489534</a>
    <br> You can also RSVP on Meetup: 
   <br> 
    <a href="https://www.meetup.com/meditation-classes/events/" target="_blank" rel="noopener">https://www.meetup.com/meditation-classes/events/</a>
    <!-- This project is served and bundled with
    <a href="https://vite.dev/guide/features.html" target="_blank" rel="noopener">Vite</a>. The
    recommended IDE setup is
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener">VSCode</a>
    +
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener">Volar</a>. If
    you need to test your components and web pages, check out
    <a href="https://vitest.dev/" target="_blank" rel="noopener">Vite</a>
    and
    <a href="https://www.cypress.io/" target="_blank" rel="noopener">Cypress</a>
    /
    <a href="https://playwright.dev/" target="_blank" rel="noopener">Playwright</a>.

    <br />

    More instructions are available in
    <a href="javascript:void(0)" @click="openReadmeInEditor"><code>README.md</code></a
    >. -->
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>How does this work?</template>
    As you move through your day—working, cleaning, running errands—you’ll treat each task as an extension of your practice. Inspired by Plum Village traditions, we pause together for a brief, 5-minute meditation at 55 minutes past each hour or 20minutes. We alternate each hour.(See schedule.) These short breaks refocus our attention and reconnect us with the awareness we’re cultivating, reminding us to bring mindful presence into everything we do.
    <!-- Get official tools and libraries for your project:
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener">Pinia</a>,
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener">Vue Router</a>,
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener">Vue Test Utils</a>, and
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener">Vue Dev Tools</a>. If
    you need more resources, we suggest paying
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">Awesome Vue</a>
    a visit. -->
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Who is this for?</template>
    Anyone trying to bring more mindfulness into their life.
    Any level of meditation experience is welcome.
    We have found people that enjoy this are:
    <ul>
      <li>People looking to get more done that have to work/do chores on the weekend</li>
      <li>People looking to reduce stress and anxiety(the zen of stress?)</li>
      <li>Someone with a meditation practice looking for a sangha (community) to support their practice on the weekend</li>
      <li>People looking to change their usualy way of thinking/feeling/being</li>
    </ul>
    <!-- We do silent meditation, which is challenging for some.
    So we will also leave links to guided meditations, that someone can do instead. -->
<!-- 
    Got stuck? Ask your question on
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Vue Land</a>
    (our official Discord server), or
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      >StackOverflow</a
    >. You should also follow the official
    <a href="https://bsky.app/profile/vuejs.org" target="_blank" rel="noopener">@vuejs.org</a>
    Bluesky account or the
    <a href="https://x.com/vuejs" target="_blank" rel="noopener">@vuejs</a>
    X account for latest news in the Vue world. -->
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Us By Just Showing Up and Pracitcing</template>

    This event is free and always will be.
    If you want to donate to support this and similiar ventures check out:
    <a href="https://living-meditation.org/" target="_blank" rel="noopener">Our sister Project</a>.
  </WelcomeItem>
</template>
