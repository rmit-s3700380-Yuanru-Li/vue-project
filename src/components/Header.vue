<template>
  <div class="d-flex flex-row justify-content-between m-0 px-5 bg-header w-100 shadow mb-3">
    <div class="row align-items-center" style="height:100px;">
      <img alt="Patc logo" src="../assets/logo.png" />
      <p class="h2 ml-3">People At The Centre</p>
    </div>
    <div class="row align-items-center" style="height:100px;">
      <div class="dropdown mr-5">
        <svg
          class="bi bi-list dropdown-toggle"
          width="3em"
          height="3em"
          viewBox="0 0 16 16"
          fill="currentColor"
          xmlns="http://www.w3.org/2000/svg"
          data-toggle="dropdown"
          aria-haspopup="true"
          aria-expanded="false"
        >
          <path
            fill-rule="evenodd"
            d="M2.5 11.5A.5.5 0 013 11h10a.5.5 0 010 1H3a.5.5 0 01-.5-.5zm0-4A.5.5 0 013 7h10a.5.5 0 010 1H3a.5.5 0 01-.5-.5zm0-4A.5.5 0 013 3h10a.5.5 0 010 1H3a.5.5 0 01-.5-.5z"
            clip-rule="evenodd"
          />
        </svg>
        <div class="dropdown-menu mt-4 ml-n5" aria-labelledby="dropdownMenuButton">
          <a class="dropdown-item listIcon " href="#">Post Job Ad</a>
          <a class="dropdown-item listIcon" href="#">Shortlist Candidates</a>
          <a class="dropdown-item listIcon" href="#">Interview Maintenance</a>
          <a class="dropdown-item listIcon" href="#">PATC Video Interview sample</a>
          <a class="dropdown-item listIcon" href="#">About Us</a>
          <a class="dropdown-item listIcon" href="#">Contact Us</a>
        </div>
      </div>
      <div class="row align-items-center" style="height:100px;">
        <img class="rounded-circle" width="50px" height="50px" alt="Patc logo" src="../../static/images/icon.png" />
      </div>
      <div class="row align-items-center ml-3" style="height:100px;">
        <div class="ml-2">Allison Doy</div>
        <svg
          class="bi bi-chevron-down ml-2"
          width="1.5em"
          height="1.5em"
          viewBox="0 0 16 16"
          fill="currentColor"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            fill-rule="evenodd"
            d="M1.646 4.646a.5.5 0 01.708 0L8 10.293l5.646-5.647a.5.5 0 01.708.708l-6 6a.5.5 0 01-.708 0l-6-6a.5.5 0 010-.708z"
            clip-rule="evenodd"
          />
        </svg>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "AppHeader",
  data() {
  },
  methods: {}
};
</script>
