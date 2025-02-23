<script setup lang="ts"></script>

<template>
  <section id="contact">
    <div class="mt-16 text-center">
      <h1 class="text-4xl lg:text-5xl font-bold lg:tracking-tight">
        <span class="text-primary poppins">Contato</span>
      </h1>
    </div>
    <div
      class="bg-[radial-gradient(ellipse_at_center,_var(--tw-gradient-stops))] from-primary-900 to-transparent rounded-full h-80 w-80 z-0 blur-lg absolute top-3/4 -left-4 transform -translate-x-1/2 -translate-1/2"></div>
    <div class="grid md:grid-cols-2 py-24 gap-4 relative">
      <div>
        <h2 class="text-xl font-bold my-2">Vamos nos conectar</h2>
        <p class="mb-4 max-w-md">
          Não hesite em me enviar uma mensagem ou um e-mail.
          Entrarei em contato com você o mais rápido possível.
        </p>
        <div class="flex flex-col gap-4 text-xl">
          <div class="flex flex-row gap-x-6">
            <a
              href="https://github.com/regiszaum"
              target="_blank"
              class="hover:text-primary"
              aria-label="GitHub Profile">
              Github
              <Icon
                name="fa6-brands:github"
                class="size-8" />
            </a>
            <a
              href="https://www.linkedin.com/in/regisadrianofilho/"
              target="_blank"
              class="hover:text-primary"
              aria-label="LinkedIn Profile">
              Linkedin
              <Icon
                name="fa6-brands:linkedin"
                class="size-8" />
            </a>
          </div>
          <div class="flex flex-row items-center">
            <a
              href="mailto:regisf97@gmail.com"
              class="text-base md:text-lg font-bold hover:text-primary">
              <Icon
                name="fa6-solid:envelope"
                class="size-6" />
              regisf97@gmail.com</a
            >
          </div>
        </div>
      </div>
      <div>
        <form class="flex flex-col">
          <div class="mb-6">
            <label
              for="email"
              class="block mb-2 text-sm font-medium"
              >Seu email</label
            ><input
              type="email"
              id="email"
              required
              class="bg-white/10 border border-primary text-sm outline-none rounded-md block w-full p-3 focus:ring-2 ring-primary"
              placeholder="joao@exemplo.com"
              name="email" />
          </div>
          <div class="mb-6">
            <label
              for="subject"
              class="block text-sm mb-2 font-medium"
              >Assunto</label
            ><input
              type="text"
              id="subject"
              required
              class="bg-white/10 border border-primary text-sm outline-none rounded-md block w-full p-3 focus:ring-2 ring-primary"
              placeholder="Assunto da sua mensagem"
              name="subject" />
          </div>
          <div class="mb-6">
            <label
              for="message"
              class="block text-sm mb-2 font-medium"
              >Mensagem</label
            ><textarea
              name="message"
              id="message"
              class="bg-white/10 border border-primary text-sm outline-none rounded-md block w-full p-3 focus:ring-2 ring-primary"
              placeholder="Vamos falar sobre..."></textarea>
          </div>
          <button
            type="submit"
            class="bg-primary hover:bg-blue-300 font-extrabold py-2.5 px-5 rounded-lg w-full">
            Enviar mensagem
          </button>
        </form>
      </div>
    </div>
  </section>
</template>
