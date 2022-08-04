<script>

</script>

<div class="columns">
    <section class="section column is-one-third">
        <div class="card has-no-rounded is-bg-cover is-cursor-pointer transform is-duration-300 hover-translate-y" style="background-image: url('https://images.unsplash.com/photo-1526763025764-2a8073a0cd43?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80');">
            <div class="card-content has-no-rounded is-duration-300 pt-24">
                <div class="content">
                    <div class="title-transform-y is-duration-300 mb-5">
                        <h3 class="has-text-white-bis">Dummy text title</h3>
                        <div class="underline-br"></div>
                    </div>
                    <div class="text-motion has-text-white-bis transform is-duration-300 hover-translate-y">
                        <p class="is-size-6">Lorem ipsum leo risus, porta ac thes consectetur ac,
                        vestibulum at eros. Donec id elit non miy losre..</p>
                    </div>
                </div>
            </div>
        </div>
    </section>



    <section class="section column is-one-third">
        <div class="card shadow-lg is-cursor-pointer">
            <div class="card-image cover-image is-overflow-hidden">
              <figure class="image">
                <img src="https://source.unsplash.com/user/himiwaybikes" alt="Placeholder image">
              </figure>
            </div>
            <div class="card-content">
                <div class="content has-text-grey-light">
                    <h3>Dummy Text</h3>
                    Lorem ipsum leo risus, porta ac consectetur ac, vestibulum at eros. Donec id elit non miy
                </div>
            </div>
            <footer class="card-footer has-background-white-bis">
              <a href="#" class="card-footer-item p-5 has-text-grey is-uppercase is-text-wide-1">
                  Continue Reading
              </a>
            </footer>
        </div>
    </section>
    
</div>

<style>
    .pt-24 {
  padding-top: 24rem !important;
}

.is-bg-cover {
    background-repeat: no-repeat;
    background-size: cover;
}

.has-no-rounded {
    border-radius: 0px !important;
}


.is-cursor-pointer {
    cursor: pointer !important;
}

.transform {
    -webkit-transform: translateX(0) translateY(0) rotate(0) skewX(0) skewY(0) scaleX(1) scaleY(1);
    transform: translateX(0) translateY(0) rotate(0) skewX(0) skewY(0) scaleX(1) scaleY(1);
}

.is-duration-300 {
    transition-duration: 0.3s;
}

.is-bg-cover .card-content {
  background-color: rgba(0, 0, 0, 0.02);
}

.is-bg-cover:hover .card-content {
  background-color: rgba(0, 0, 0, 0.75);
}

.title-transform-y {
  -webkit-transform: translateX(0) translateY(5rem) rotate(0) skewX(0) skewY(0) scaleX(1) scaleY(1);
  transform: translateX(0) translateY(5rem) rotate(0) skewX(0) skewY(0) scaleX(1) scaleY(1);
}

.underline-br {
  width: 5rem;
  height: 0.5rem;
  background-color: yellow;
}

.text-motion {
  opacity: 0;
}

.is-bg-cover:hover .card-content .text-motion {
  opacity: 1;
}

.is-bg-cover:hover .title-transform-y {
  -webkit-transform: translateX(0) translateY(0) rotate(0) skewX(0) skewY(0) scaleX(1) scaleY(1);
  transform: translateX(0) translateY(0) rotate(0) skewX(0) skewY(0) scaleX(1) scaleY(1);
}


.cover-image {
    max-height: 330px;
    border-top-left-radius: 3px;
    border-top-right-radius: 3px;
}

.cover-image img {
    transition: transform 1s, filter 2s ease-in-out;
    -webkit-transition: transform 1s, filter 2s ease-in-out;
    transform: scale(1.1);
    -webkit-transform: scale(1.1);
}

.card:hover .cover-image img {
    cursor: pointer;
    transform: scale(1.2);
    -webkit-transform: scale(1.2);
}

.is-overflow-hidden {
    overflow: hidden !important;
}

.is-cursor-pointer {
    cursor: pointer !important;
}

.shadow-lg {
    box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05) !important;
}
</style>