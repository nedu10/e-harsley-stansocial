<template>
  <nav
    class="navbar navbar-expand-md navbar-light bg-transparant container py-4"
  >
    <a class="navbar-brand" href="#">
      <img src="/svgs/logo.svg" />
    </a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item mx-3 ">
          <a class="nav-link c-nav-text text-capitalize" href="#"
            >How it works</a
          >
        </li>
        <li class="nav-item mx-3 ">
          <a class="nav-link c-nav-text text-capitalize" href="#">Porks</a>
        </li>
        <li class="nav-item mx-3">
          <button class="btn btn-danger-custom px-4">
            Register
          </button>
        </li>
      </ul>
    </div>
  </nav>
</template>
<style>
.btn-danger-custom,
.btn-danger-custom:hover,
.btn-danger-custom:active {
  background-color: #bc0303;
  border-color: #cd1627;
  border-radius: 5px;
  font-weight: 500;
  color: white;
  border-radius: 0.1rem;
}
.c-nav-text {
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 20px;
  color: white !important;
}
</style>
