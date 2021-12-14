<template>
    <header class="p-3 mb-3 border-bottom">
        <div class="container">
            <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
                <a href="/#/alltickets" class="d-flex align-items-center mb-3 mb-lg-0 me-lg-auto text-dark text-decoration-none">
                    <span class="fs-2"><i class="bi bi-emoji-laughing bi me-2"></i>趣訂票</span>
                </a>

                <form class="col-12 col-lg-auto mb-3 mb-lg-0 me-lg-3">
                <input type="search" class="form-control" placeholder="Search..." aria-label="Search">
                </form>

                <div class="dropdown text-end">
                <a href="#" class="d-block link-dark text-decoration-none dropdown-toggle" id="dropdownUser1" data-bs-toggle="dropdown" aria-expanded="false">
                     <span class="fs-2"><i class="bi bi-person rounded-circle"></i></span>
                </a>
                <ul class="dropdown-menu text-small" aria-labelledby="dropdownUser1" style="">
                    <li><a class="dropdown-item" href="#">個人資料</a></li>
                    <li><a class="dropdown-item" href="#">查詢訂單</a></li>
                    <li><a class="dropdown-item" href="#">賣家中心</a></li>
                    <li><hr class="dropdown-divider"></li>
                    <li><a class="dropdown-item" href="#">登出</a></li>
                </ul>
                </div>
            </div>
        </div>
    </header>
</template>
<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  components: {

  },
})
export default class Header extends Vue {}
</script>
