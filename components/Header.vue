<!-- Please remove this file from your project -->
<template>
  <header id="header">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <nav class="navbar navbar-expand-lg navbar-light">
            <div class="container-fluid m-0 p-0">
              <a class="navbar-brand" href="/"
                ><img src="../assets/images/logo.svg" alt=""
              /></a>
              <button
                class="navbar-toggler"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent"
                aria-expanded="false"
                aria-label="Toggle navigation"
              >
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                  <li class="nav-item">
                    <a
                      class="nav-link active"
                      aria-current="page"
                      href="aboutUs"
                      >About Us</a
                    >
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Our Work</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Service</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">
                      <img
                        src="../assets/images/landline-icon.svg"
                        alt=""
                        width="18px"
                        class="me-2"
                      />
                      +977 9861486613</a
                    >
                  </li>
                  <li class="nav-item">
                    <a class="btn btn-first" href="#">Contact Us</a>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>
