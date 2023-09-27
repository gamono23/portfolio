<template>
    <div>
        <div class="navbarmain">
            <div class="ui">
                <div class="ghnav"><a href="https://github.com/gamono23">GitHub</a></div>
            </div>
        </div>
        <slot />
    </div>
</template>
<style>
.navbarmain{
    position: fixed;
    top: 0;
    right: 0;
    left: 0;
    margin: 0;
    width: 100vw;
    background: rgba(0,0,0,.75);
    font-size: 19px;
}
.ui{
    display: flex;
    width: 100%;
    height: 44px;
    justify-content: center;
    align-items: center;
    color:white;
    font-family: 'San Francisco';
}
a{
  color: white;
  background-color: transparent;
  text-decoration: none;
  margin-right:-50%;
}
</style>