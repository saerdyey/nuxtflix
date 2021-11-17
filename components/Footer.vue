<template>
  <div class="footer">
    <div class="footer-wrapper">
      <p>Created by Jay Anton V. Roblico</p>
      <p>
        Inspired from
        <a href="https://www.youtube.com/channel/UCr0D7PVNOHqB3Td7lVl_LKw"
          >John Komarnicki's YT channel</a
        >
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.footer {
  height: 64px;
  overflow: hidden;
  display: flex;
  &:hover {
    .footer-wrapper {
      transform: translateY(0);
      transition: 0.25s ease-in-out;
    }
  }
  .footer-wrapper {
    flex: 1;
    height: 64px;
    background-color: #891b02;
    color: #fff;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    transition: 0.5s ease-in-out;

    transform: translateY(100%);
  }
  a {
    color: inherit;
  }
}
</style>
