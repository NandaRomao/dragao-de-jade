<template>
  <div>
    <nav class="flex gap-4 p-4 bg-emerald-800 text-white">
      <NuxtLink to="/">Painel</NuxtLink>
      <NuxtLink to="/pipeline">Pipeline</NuxtLink>
      <NuxtLink to="/trends">Tendências</NuxtLink>
      <NuxtLink to="/content">Conteúdo</NuxtLink>
      <NuxtLink to="/history">Histórico</NuxtLink>
    </nav>
    <NuxtPage />
  </div>
</template>