<template>
  <nav class="nav has-shadow">
    <div class="container">
      <router-link class="nav-item is-tab" to="/">
        <div class="dropdown is-hoverable">
          <div class="dropdown-trigger">
            <span>Home</span>
            <span class="icon is-small">
              <i class="fa fa-angle-down" aria-hidden="true"></i>
            </span>
          </div>
          <div class="dropdown-menu" id="dropdown-menu4" role="menu">
            <div class="dropdown-content">
              <div class="dropdown-item">
                <p>You can insert <strong>any type of content</strong> within the dropdown menu.</p>
              </div>
            </div>
          </div>
        </div>
      </router-link>
      <router-link class="nav-item is-tab" to="/new-match">New Match</router-link>
    </div>
  </nav>
</template>
