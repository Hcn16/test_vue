

<template>
    
    
    <div class="about">
      <h1>This is an Create page</h1>
      <RouterLink to="/create/detail/" >details</RouterLink>
      <router-view></router-view>

    </div>
  </template>
  
  <style>
  @media (min-width: 1024px) {
    .about {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }
  }
  </style>
  