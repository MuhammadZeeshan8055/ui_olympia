<template>
  <section class="header">
    <header>
      <div class="container">
        <div class="row-fluid flexbox">
          <div class="col-12 col-mid-12">
            <nav>
              <input type="checkbox" id="check" name="" value="">
              <label for="check" id="checkbtn"><i class="fa fa-bars"></i></label>
              <NuxtLink to="/">
                <img class="desktop-logo" src="/images_folder/logos/olympia-india-logo.png" alt="Desktop Logo"
                  width="220" height="80">
              </NuxtLink>
              <div class="mobile-logo logo_wrapper">
                <img class="mobile-logo" src="/images_folder/logos/olympia_logomark.png" alt="mobile Logo" width="200"
                  height="80">
              </div>
              <ul>
                <li class="dropdown">

                  <div class="inside-dropdown-mobile-logo">
                    <label for="dummy" id="dummy"><i class="fr fa-solid fa-xmark" style="color:white"></i></label>
                    <img class="inside-dropdown-mobile-logo-img" src="/images_folder/logos/olympia_logomark.png"
                      alt="mobile Logo" width="100" height="100">
                    <label for="check" id="checkbtn"><i class="fr fa-solid fa-xmark" style="color:black"></i></label>
                  </div>

                  <hr class="nav-title-bottom-line-full-width">

                  <a href="#" class="books-category-title">Books <i
                      class="fr outer-chevron-icon fa-solid fa-chevron-down"></i><i
                      class="fr fa-solid fa-chevron-up"></i></a>
                  <div class="dropdown-content">
                    <div class="container">
                      <div class="row-fluid flexbox flex-wrap">
                        <div class="col-2 col-mid-2 col-xs-12"></div>
                        <div class="col-2 col-mid-2 col-xs-12">

                          <div class="fiction-books-category">
                            <p class="mb-5 toggle-heading active">Fiction <i
                                class="heading fr fa-solid fa-chevron-down"></i> <i
                                class="heading fr fa-solid fa-chevron-up"></i></p>
                            <ol class="fiction-list">
                              <li><a href="" class="book-category">Activity Book</a></li>
                              <li><a href="" class="book-category">Adult Fiction</a></li>
                              <li><a href="" class="book-category">Adventure & Fantasy</a></li>
                              <li><a href="" class="book-category">Animals</a></li>
                              <li><a href="" class="book-category">Colouring Books</a></li>
                              <li><a href="" class="book-category">Crime</a></li>
                              <li><a href="" class="book-category">General Fiction</a></li>
                              <li><a href="" class="book-category">Historical</a></li>
                              <li><a href="" class="book-category">Horror</a></li>
                              <li><a href="" class="book-category">Humor</a></li>
                              <li><a href="" class="book-category">Middle Grade Fiction</a></li>
                              <li><a href="" class="book-category">Mystery</a></li>
                              <li><a href="" class="book-category">Poetry</a></li>
                              <li><a href="" class="book-category">Romance</a></li>
                              <li><a href="" class="book-category">Science-Fiction</a></li>
                              <li><a href="" class="book-category">Short Stories</a></li>
                              <li><a href="" class="book-category">Thriller</a></li>
                              <li><a href="" class="book-category">War</a></li>
                              <li><a href="" class="book-category">Young Adult Fiction</a></li>
                              <li><a href="" class="book-category">View all fiction <i
                                    class="fas fa-chevron-right"></i></a></li> <!-- Font Awesome icon -->
                            </ol>
                            <hr class="mobile-section">
                          </div>
                        </div>
                        <div class="col-2 col-mid-2 col-xs-12">

                          <!-- Non-Fiction Books Category -->
                          <div class="fiction-books-category">
                            <p class="mb-5 toggle-heading">Non Fiction <i
                                class="heading fr fa-solid fa-chevron-down"></i> <i
                                class="heading fr fa-solid fa-chevron-up"></i></p>
                            <ol class="fiction-list">
                              <li><a href="" class="book-category">Autobiographical</a></li>
                              <li><a href="" class="book-category">Biographical & Memoirs</a></li>
                              <li><a href="" class="book-category">Educational</a></li>
                              <li><a href="" class="book-category">Food & Drink</a></li>
                              <li><a href="" class="book-category">Health</a></li>
                              <li><a href="" class="book-category">Lifestyle</a></li>
                              <li><a href="" class="book-category">Memoirs</a></li>
                              <li><a href="" class="book-category">Personal Development</a></li>
                              <li><a href="" class="book-category">Pets</a></li>
                              <li><a href="" class="book-category">Philosophy</a></li>
                              <li><a href="" class="book-category">Religion</a></li>
                              <li><a href="" class="book-category">Self Help</a></li>
                              <li><a href="" class="book-category">Spirituality</a></li>
                              <li><a href="" class="book-category">Sport</a></li>
                              <li><a href="" class="book-category">Travel and Holidays</a></li>
                              <li><a href="" class="book-category">View all non-fiction <i
                                    class="fas fa-chevron-right"></i></a></li> <!-- Font Awesome icon -->
                            </ol>
                            <hr class="mobile-section">
                          </div>
                        </div>
                        <div class="col-2 col-mid-2 col-xs-12">

                          <div class="fiction-books-category">
                            <p class="mb-5 toggle-heading">Bumblebee books <i
                                class="heading fr fa-solid fa-chevron-down"></i> <i
                                class="heading fr fa-solid fa-chevron-up"></i></p>
                            <ol class="fiction-list">
                              <li><a href="" class="book-category">Children's bestsellers</a></li>
                              <li><a href="" class="book-category">Children's fiction</a></li>
                              <li><a href="" class="book-category">Children's non-fiction</a></li>
                              <li><a href="" class="book-category"><img
                                    src="/images_folder/images/about_us_Bumblebee logo.png"
                                    class="category-bumblebee-logo" alt=""></a></li>
                              <li><a href="" class="book-category">View all Bumblebee books <i
                                    class="fa-solid fa-chevron-right"></i></a></li>
                            </ol>
                            <hr class="mobile-section">
                          </div>
                        </div>
                        <div class="col-2 col-mid-2 col-xs-12">
                          <div class="fiction-books-category">

                            <ol class="fiction-list-last-part">

                              <li><a href="" class="book-category">Bestsellers</a></li>
                              <li><a href="" class="book-category">What we’re reading</a></li>
                              <li><a href="" class="book-category">Children’s top picks</a></li>

                            </ol>


                          </div>
                        </div>
                        <div class="col-1 col-mid-1 col-xs-12"></div>

                      </div>
                    </div>
                    <!-- Add more books as needed -->
                  </div>
                </li>
                <li>
                  <a href="#">Authors</a>

                </li>
                <li>
                  <NuxtLink to="/feature">Features</NuxtLink>
                </li>
                <li>
                  <a href="#">About us</a>

                </li>
                <li>
                  <a href="#">Publish with us</a>

                </li>
                <li><a href="#"><button class="online-submit-button">Submit Online</button></a></li>
                <li class="dropdown">
                  <a href="">
                    <i class="desktop-navbar-search fa-solid fa-magnifying-glass" style="color:black"></i>

                  </a>
                  <div class="dropdown-content search-box">
                    <div class="container-fluid">
                      <div class="row-fluid flexbox flex-wrap top-search-box-row">

                        <div class="col-2 col-xs-2">
                          <img class="searchbox-desktop-logo" src="/images_folder/logos/olympia-india-logo.png"
                            alt="Desktop Logo" width="200" height="80">
                        </div>
                        <div class="col-8 col-xs-8">
                          <form action="">
                            <input type="search" name="" id="" class="search-box-input"
                              placeholder="Search for books, authors and articles">
                          </form>
                        </div>
                        <div class="col-2 col-xs-2">
                          <a href="" class="cross-button-style">
                            <i class="cross-navbar-search fa-solid fa-xmark" style="color:black"></i>
                          </a>
                        </div>


                      </div>

                      <hr class="title-bottom-line-full-width">

                      <div class="row-fluid flexbox flex-wrap">
                        <div class="col-2 col-xs-2"></div>
                        <div class="col-7 col-xs-8">
                          <div class="search-box-content mt-5">
                            <p class="search-box-content-title">Books</p>
                            <p class="search-box-content-highlighted-text space-2">Books <span>Author Name</span> </p>
                            <p class="search-box-content-text space-2">Books <span>Author Name</span></p>
                            <p class="search-box-content-text space-2">Books <span>Author Name</span></p>
                            <p class="search-box-content-text space-2">Books <span>Author Name</span></p>
                          </div>
                          <div class="search-box-content mt-5">
                            <p class="search-box-content-title">Authors</p>
                            <p class="search-box-content-highlighted-text space-2"><i class="fa-solid fa-circle"></i>
                              Author Name</p>
                            <p class="search-box-content-text space-2"><i class="fa-solid fa-circle"></i> Author Name
                            </p>
                            <p class="search-box-content-text space-2"><i class="fa-solid fa-circle"></i> Author Name
                            </p>
                          </div>
                          <div class="search-box-content mt-5">
                            <p class="search-box-content-title">Features</p>
                            <p class="search-box-content-highlighted-text space-2"><small>Article category</small>
                              Article title - Lorem ipsum dolor sit amet</p>
                            <p class="search-box-content-text space-2"><small>Article category</small> Article title -
                              Lorem ipsum dolor sit amet</p>
                            <p class="search-box-content-text space-2"><small>Article category</small> Article title -
                              Lorem ipsum dolor sit amet</p>
                          </div>
                        </div>
                        <div class="col-3 col-xs-2"></div>

                        <div class="col-12 col-xs-12 text-center space-5">
                          <a href="" class="search-box-view-all-link">View all results <i
                              class="fa-solid fa-chevron-right"></i></a>
                        </div>

                      </div>


                    </div>


                    <!-- Add more books as needed -->
                  </div>

                </li>
              </ul>
              <input type="checkbox" id="searchcheck" name="" value="">
              <label for="searchcheck" id="searchbtn"><i class="fa fa-search"></i></label>

              <div class="search-box-mobile">
                <div class="container">
                  <div class="row flexbox flex-wrap mobile-search mb-5">
                    <div class="col-xs-2">
                      <a href=""><i class="fa fa-search inside-search-container"></i></a>

                    </div>
                    <div class="col-xs-8">
                      <input type="search" placeholder="Search for books,authors and articles"
                        class="search-box-mobile-input">
                    </div>
                    <div class="col-xs-2">

                      <a id="closeSearch"><i class="fa fa-times fr inside-search-container"></i></a>
                    </div>
                  </div>

                  <hr class="title-bottom-line-full-width">

                  <div class="row flexbox flex-wrap mt-5">
                    <div class="col-xs-12">
                      <div class="books-mobile-search-title">
                        <p class="books-title"><span>(5)</span> Books</p>
                        <p class="authors-title"><span>(3)</span> Authors</p>
                        <p class="features-title"><span>(3)</span> Features</p>
                      </div>
                    </div>

                    <div class="col-xs-12 mt-5 space-5">
                      <div id="books-search-category" class="active">
                        <p class="search-box-content-text space-2">Books <span>Author Name</span></p>
                        <p class="search-box-content-text space-2">Books <span>Author Name</span></p>
                        <p class="search-box-content-text space-2">Books <span>Author Name</span></p>
                        <p class="search-box-content-text space-2">Books <span>Author Name</span></p>
                        <p class="search-box-content-text space-2">Books <span>Author Name</span></p>
                      </div>
                      <div id="authors-search-category" class="hidden">
                        <p class="search-box-content-text space-2"><i class="fa-solid fa-circle"></i> Author Name</p>
                        <p class="search-box-content-text space-2"><i class="fa-solid fa-circle"></i> Author Name</p>
                        <p class="search-box-content-text space-2"><i class="fa-solid fa-circle"></i> Author Name</p>
                      </div>
                      <div id="features-search-category" class="hidden">
                        <p class="search-box-content-text space-2"><small>Article category</small> Article title - Lorem
                          ipsum dolor sit amet</p>
                        <p class="search-box-content-text space-2"><small>Article category</small> Article title - Lorem
                          ipsum dolor sit amet</p>
                        <p class="search-box-content-text space-2"><small>Article category</small> Article title - Lorem
                          ipsum dolor sit amet</p>
                      </div>
                    </div>
                  </div>

                </div>


              </div>



            </nav>
          </div>
        </div>
      </div>

    </header>
  </section>



</template>
<script>
export default {
  name: "Header"
}
</script>
