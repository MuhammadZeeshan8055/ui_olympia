<template>
  <section class="footer margin-top-5">
    <footer>

      <div class="container footer-section-margin space-5">
        <div class="row-fluid flexbox flex-wrap">

          <div class="col-3 col-xs-12 col-mid-4 footer-section-margin">
            <p class="footer-title" id="useful-links">Useful links <i class="fr fa-solid fa-chevron-up"></i></p>
            <hr class="title-bottom-line-indianred">
            <ul class="footer-section-margin links" id="useful-links-list">
              <li><a href="">Submit online</a></li>
              <li><a href="">Publish with us</a></li>
              <li><a href="">About us</a></li>
              <li><a href="">Contact us</a></li>
              <li><a href="">Bumblebee books</a></li>
              <li><a href="">Author experiences</a></li>
              <li><a href="">Publishing process</a></li>
            </ul>
          </div>

          <div class="col-3 col-xs-12 col-mid-4 footer-section-margin">
            <p class="footer-title" id="olympia-publishers">Olympia Publishers India <i
                class="fr fa-solid fa-chevron-down"></i></p>
            <hr class="title-bottom-line-indianred">
            <ul class="footer-section-margin links" id="olympia-publishers-list">
              <li><a href="">Alpha</a></li>
              <li><a href="">2nd Floor, No. 201,</a></li>
              <li><a href="">Hiranandani Gardens, Powai</a></li>
              <li><a href="">Mumbai, 400 076</a></li>
              <li><a href="">E: info@olympiapublishers.in</a></li>
            </ul>
          </div>

          <div class="col-3 col-xs-12 col-mid-4 footer-section-margin">
            <p class="footer-title" id="global-location">Global locations <i class="fr fa-solid fa-chevron-down"></i>
            </p>
            <hr class="title-bottom-line-indianred">
            <ul class="footer-section-margin links" id="global-location-list">
              <li><a href="">India</a></li>
              <li><a href="">UK</a></li>
              <li><a href="">USA</a></li>
            </ul>
          </div>
          <div class="col-3 col-mid-6 col-xs-12 footer-section-margin">
            <p class="footer-title">Connect to Olympia Publishers</p>
            <hr class="title-bottom-line-indianred">
            <ul class="footer-section-margin">
              <li>
                <div class="footer-social-icons">
                  <a href="" class="p-2">
                    <img class="social-icons" src="\images_folder\social_icons\1161954_instagram_icon.png" height="40px"
                      width="40px" alt="">
                  </a>
                  <a href="" class="p-2">
                    <img class="social-icons" src="\images_folder\social_icons\104445_video_youtube_icon.png"
                      height="40px" width="40px" alt="">
                  </a>
                  <a href="" class="p-2">
                    <img class="social-icons"
                      src="\images_folder\social_icons\104458_facebook_social media_fb_social_icon.png" height="40px"
                      width="40px" alt="">
                  </a>
                  <a href="" class="p-2">
                    <img class="social-icons" src="\images_folder\social_icons\104461_twitter_icon.png" height="40px"
                      width="40px" alt="">
                  </a>
                  <a href="" class="p-2">
                    <img class="social-icons" src="\images_folder\social_icons\104430_pinterest_icon.png" height="40px"
                      width="40px" alt="">
                  </a>
                </div>

              </li>


              <li class="footer-section-margin">
                <a href="">Connect to Bumblebee Books</a>
                <hr class="title-bottom-line-yellow">

              </li>

              <li>
                <div class="footer-social-icons">
                  <a href="" class="p-2">
                    <img class="social-icons" src="\images_folder\social_icons\1161954_instagram_icon.png" height="40px"
                      width="40px" alt="">
                  </a>
                  <a href="" class="p-2">
                    <img class="social-icons" src="\images_folder\social_icons\104445_video_youtube_icon.png"
                      height="40px" width="40px" alt="">
                  </a>
                  <a href="" class="p-2">
                    <img class="social-icons"
                      src="\images_folder\social_icons\104458_facebook_social media_fb_social_icon.png" height="40px"
                      width="40px" alt="">
                  </a>
                  <a href="" class="p-2">
                    <img class="social-icons" src="\images_folder\social_icons\104461_twitter_icon.png" height="40px"
                      width="40px" alt="">
                  </a>
                  <a href="" class="p-2">
                    <img class="social-icons" src="\images_folder\social_icons\104430_pinterest_icon.png" height="40px"
                      width="40px" alt="">
                  </a>
                </div>
              </li>



            </ul>
          </div>


        </div>
      </div>

      <hr class="title-bottom-line-full-width">


      <div class="container">

        <div class="row-fluid">

          <div class="col-12">
            <div class="footer-logos flexbox">
              <img src="\images_folder\logos\olympia_logomark.png" height="70px" width="70px" alt="">
              <img src="\images_folder\logos\bumblebee_logomark.png" height="70px" width="70px" alt="">
              <img src="\images_folder\logos\authorshub_logomark.png" height="55px" width="60px" alt="">

            </div>

          </div>
          <div class="col-12">
            <div class="footer-end-section text-center">
              <p class="rights">Bumblebee Books is an imprint of Olympia Publishers. © 2021 Ashwell Publishing Ltd
              </p>
              <p class="terms_conditions">Terms & Conditions | Privacy & Cookies Policy</p>
            </div>

          </div>

        </div>

      </div>

    </footer>

  </section>

</template>
<script>
export default {
  name: "Header",

  mounted() {

    // hero section
    $('.hero-section-slider').slick({
      dots: true,
      infinite: true,
      speed: 300,
      slidesToShow: 1,
      adaptiveHeight: true
    });


    // books section
    $('.slider').slick({
      dots: true,
      infinite: true,
      speed: 300,
      slidesToShow: 6,
      slidesToScroll: 4,
      responsive: [{
        breakpoint: 1024,
        settings: {
          slidesToShow: 3,
          slidesToScroll: 3,
          infinite: true,
          dots: true
        }
      },
      {
        breakpoint: 600,
        settings: {
          slidesToShow: 2,
          slidesToScroll: 2
        }
      },
      {
        breakpoint: 480,
        settings: {
          slidesToShow: 2,
          slidesToScroll: 1
        }
      }
        // You can unslick at a given breakpoint now by adding:
        // settings: "unslick"
        // instead of a settings object
      ]
    });


    // description-mobile-sections section
    $('.description-mobile-sections-slider').slick({
      dots: true,
      infinite: true,
      speed: 300,
      slidesToShow: 1,
      slidesToScroll: 1,
      responsive: [{
        breakpoint: 1024,
        settings: {
          slidesToShow: 1,
          slidesToScroll: 1,
          infinite: true,
          dots: true
        }
      },
      {
        breakpoint: 600,
        settings: {
          slidesToShow: 1,
          slidesToScroll: 1
        }
      },
      {
        breakpoint: 480,
        settings: {
          slidesToShow: 1,
          slidesToScroll: 1
        }
      }
        // You can unslick at a given breakpoint now by adding:
        // settings: "unslick"
        // instead of a settings object
      ]
    });

    // childrens-books section
    $('.childrens-book-slider').slick({
      dots: true,
      infinite: true,
      speed: 300,
      slidesToShow: 6,
      slidesToScroll: 4,
      responsive: [{
        breakpoint: 1024,
        settings: {
          slidesToShow: 3,
          slidesToScroll: 3,
          infinite: true,
          dots: true
        }
      },
      {
        breakpoint: 600,
        settings: {
          slidesToShow: 2,
          slidesToScroll: 2
        }
      },
      {
        breakpoint: 480,
        settings: {
          slidesToShow: 2,
          slidesToScroll: 1
        }
      }
        // You can unslick at a given breakpoint now by adding:
        // settings: "unslick"
        // instead of a settings object
      ]
    });

    // article-slider
    $('.article-slider').slick({
      dots: true,
      infinite: true,
      speed: 300,
      slidesToShow: 3,
      slidesToScroll: 4,
      responsive: [{
        breakpoint: 1024,
        settings: {
          slidesToShow: 3,
          slidesToScroll: 3,
          infinite: true,
          dots: true
        }
      },
      {
        breakpoint: 600,
        settings: {
          slidesToShow: 2,
          slidesToScroll: 2
        }
      },
      {
        breakpoint: 480,
        settings: {
          slidesToShow: 1,
          slidesToScroll: 1
        }
      }
        // You can unslick at a given breakpoint now by adding:
        // settings: "unslick"
        // instead of a settings object
      ]
    });

    // navbar dropdown code


    document.addEventListener("DOMContentLoaded", function () {
      var dropdowns = document.querySelectorAll(".dropdown");

      // Toggle dropdowns on click
      dropdowns.forEach(function (dropdown) {
        var toggleButton = dropdown.querySelector("a");
        toggleButton.addEventListener("click", function (event) {
          // Toggle active class for clicked dropdown
          dropdown.classList.toggle("active");

          // Toggle active class for .books-category-title
          var booksCategoryTitle = dropdown.querySelector(".books-category-title");
          if (booksCategoryTitle) {
            booksCategoryTitle.classList.toggle("active");
          }

          // Prevent default link behavior
          event.preventDefault();
        });

        // Prevent dropdown from closing when clicking inside it
        dropdown.addEventListener("click", function (event) {
          event.stopPropagation(); // Prevent event from bubbling up
        });

        // Close dropdowns when clicking on the x-mark icon
        var xMarkIcon = dropdown.querySelector(".cross-navbar-search");
        if (xMarkIcon) {
          xMarkIcon.addEventListener("click", function (event) {
            dropdown.classList.remove("active");
            var booksCategoryTitle = dropdown.querySelector(".books-category-title");
            if (booksCategoryTitle) {
              booksCategoryTitle.classList.remove("active");
            }
            event.preventDefault();
          });
        }

        // Prevent dropdown from closing when interacting with search input
        var searchInput = dropdown.querySelector("input[type='search']");
        if (searchInput) {
          searchInput.addEventListener("click", function (event) {
            event.stopPropagation(); // Prevent event from bubbling up
          });
        }
      });
    });

    // Add this JavaScript to handle closing the search box when the close button is clicked
    document.getElementById('closeSearch').addEventListener('click', function () {
      document.getElementById('searchcheck').checked = false;
    });

    // JavaScript code to handle click events and toggle visibility
    document.addEventListener('DOMContentLoaded', function () {
      const booksTitle = document.querySelector('.books-title');
      const authorsTitle = document.querySelector('.authors-title');
      const featuresTitle = document.querySelector('.features-title');

      const booksCategory = document.getElementById('books-search-category');
      const authorsCategory = document.getElementById('authors-search-category');
      const featuresCategory = document.getElementById('features-search-category');

      // Add active class to books title by default
      booksTitle.classList.add('active');

      booksTitle.addEventListener('click', function () {
        toggleVisibility(booksCategory);
        hideElements(authorsCategory, featuresCategory);
        setActive(booksTitle);
      });

      authorsTitle.addEventListener('click', function () {
        toggleVisibility(authorsCategory);
        hideElements(booksCategory, featuresCategory);
        setActive(authorsTitle);
      });

      featuresTitle.addEventListener('click', function () {
        toggleVisibility(featuresCategory);
        hideElements(booksCategory, authorsCategory);
        setActive(featuresTitle);
      });

      function toggleVisibility(element) {
        element.classList.toggle('hidden');
      }

      function hideElements(...elements) {
        elements.forEach(element => {
          element.classList.add('hidden');
        });
      }

      function setActive(titleElement) {
        // Remove active class from all title elements
        [booksTitle, authorsTitle, featuresTitle].forEach(element => {
          element.classList.remove('active');
        });
        // Add active class to the clicked title element
        titleElement.classList.add('active');
      }
    });

    // jQuery document ready function
    $(document).ready(function () {
      // Default to show details of book5
      var bookId = "book5";

      // Define book details based on ID (you can use a switch statement or object mapping for more books)
      var bookDetails = {
        "book1": {
          title: "MISS ANT",
          author: "Author 1",
          description: "Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dignissimos ducimus, ipsum nostrum, numquam facere iste quos tempora illo aliquid praesentium fugit inventore! In necessitatibus molestias culpa laboriosam nesciunt, illo eum quam voluptates veritatis, facilis nisi. Error alias velit nam voluptas!.",
          link: "https://example.com/book1"
        },
        "book2": {
          title: "MISS WHALE",
          author: "Author 2",
          description: "Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dignissimos ducimus, ipsum nostrum, numquam facere iste quos tempora illo aliquid praesentium fugit inventore! In necessitatibus molestias culpa laboriosam nesciunt, illo eum quam voluptates veritatis, facilis nisi. Error alias velit nam voluptas!.",
          link: "https://example.com/book2"
        },
        "book3": {
          title: "MR MONKEY",
          author: "Author 3",
          description: "Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dignissimos ducimus, ipsum nostrum, numquam facere iste quos tempora illo aliquid praesentium fugit inventore! In necessitatibus molestias culpa laboriosam nesciunt, illo eum quam voluptates veritatis, facilis nisi. Error alias velit nam voluptas!.",
          link: "https://example.com/book3"
        },
        "book4": {
          title: "MR ELEPHANT",
          author: "Author 4",
          description: "Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dignissimos ducimus, ipsum nostrum, numquam facere iste quos tempora illo aliquid praesentium fugit inventore! In necessitatibus molestias culpa laboriosam nesciunt, illo eum quam voluptates veritatis, facilis nisi. Error alias velit nam voluptas!.",
          link: "https://example.com/book4"
        },
        "book5": {
          title: "The World Belongs to Animals",
          author: "Author Name",
          description: "Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dignissimos ducimus, ipsum nostrum, numquam facere iste quos tempora illo aliquid praesentium fugit inventore! In necessitatibus molestias culpa laboriosam nesciunt, illo eum quam voluptates veritatis, facilis nisi. Error alias velit nam voluptas!",
          link: "https://example.com/book5"
        }
      };

      // Update book description section with the default book's details
      $("#book-title").text(bookDetails[bookId].title);
      $("#book-author").text(bookDetails[bookId].author);
      $("#book-description").text(bookDetails[bookId].description);
      $("#book-link").attr("href", bookDetails[bookId].link); // Update view book link href

      // Handle click event on book links
      $(".book-link").click(function (e) {
        e.preventDefault(); // Prevent default link behavior
        var clickedBookId = $(this).data('id'); // Get the ID of the clicked book

        // Update book description section with the clicked book's details
        $("#book-title").text(bookDetails[clickedBookId].title);
        $("#book-author").text(bookDetails[clickedBookId].author);
        $("#book-description").text(bookDetails[clickedBookId].description);
        $("#book-link").attr("href", bookDetails[clickedBookId].link); // Update view book link href



      });
    });


    $(document).ready(function () {
      // Check if screen width is less than or equal to 480px (typical mobile sizes)
      if ($(window).width() <= 480) {
        // Function to handle toggling of .fiction-list and active class on .toggle-heading
        $('.toggle-heading').click(function () {
          var $list = $(this).next('.fiction-list');

          // Toggle visibility of the next .fiction-list
          $list.slideToggle();

          // Collapse all other .fiction-lists except the clicked one
          $('.fiction-list').not($list).slideUp();

          // Toggle active class on .toggle-heading
          $(this).toggleClass('active');

          // Remove 'active' class from all other .toggle-heading elements
          $('.toggle-heading').not(this).removeClass('active');
        });

        // Initially hide all .fiction-lists except the one with 'active' class
        $('.toggle-heading:not(.active)').next('.fiction-list').hide();

        // Ensure the first .toggle-heading is active by default
        $('.toggle-heading.active').each(function () {
          var $list = $(this).next('.fiction-list');
          $list.show(); // Show the corresponding .fiction-list
        });
      }
    });


    function toggleActive(element) {
      element.classList.toggle('.books-category-title.active');
    }

    document.addEventListener("DOMContentLoaded", function () {
      // Select all footer titles
      const footerTitles = document.querySelectorAll(".footer-title");
      if ($(window).width() <= 480) {

        // Function to handle click on footer title
        function handleTitleClick(clickedTitle) {
          // Remove 'active' class from all titles
          footerTitles.forEach(function (title) {
            title.classList.remove("active");
          });

          // Add 'active' class to the clicked title
          clickedTitle.classList.add("active");

          // Get the corresponding list by the id
          const listId = clickedTitle.id + "-list";
          const list = document.getElementById(listId);

          // Toggle the visibility of the list
          if (list.style.display === "block") {
            list.style.display = "none";
          } else {
            list.style.display = "block";
          }
        }

        // Add click event listeners to all footer titles
        footerTitles.forEach(function (title) {
          title.addEventListener("click", function () {
            handleTitleClick(this);
          });
        });

        // Activate 'Useful links' section by default
        const defaultActiveTitle = document.getElementById("useful-links");
        handleTitleClick(defaultActiveTitle); // Set 'Useful links' as active initially
      }

    });

    $(document).ready(function () {
      $('.filter-by-title').click(function () {
        // Toggle visibility of all .filter-list elements
        $('.filter-list').slideToggle();

        // Toggle 'active' class on .filter-by-title
        $(this).toggleClass('active');

        // Toggle sidebar width based on active class
        $('.sidebar-content').toggleClass('full-screen');

        // Toggle body class for overlay and scrolling
        $('body').toggleClass('full-screen-sidebar');
      });

      // Toggle 'active' class on .filter-list items
      $('.filter-list').click(function () {
        $(this).toggleClass('active');

        // Check if any .filter-list has 'active' class
        var anyActive = $('.filter-list').hasClass('active');

        // Toggle sidebar width based on active class
        if (anyActive) {
          $('.sidebar-content').addClass('full-screen');
          $('body').addClass('full-screen-sidebar');
        } else {
          $('.sidebar-content').removeClass('full-screen');
          $('body').removeClass('full-screen-sidebar');
        }
      });
    });

    $(document).ready(function () {
      // Initially hide author image wrapper
      $('.image-wrapper-section.author').hide();

      // By default, show book details and hide author details
      $('.book-details-section').show();
      $('.authors-details-section').hide();

      // Click event for Book tab
      $('.book').click(function () {
        $(this).addClass('active');
        $('.author').removeClass('active');
        $('.book-details-section').show();
        $('.authors-details-section').hide();
        $('.image-wrapper-section.book').show();
        $('.image-wrapper-section.author').hide();
      });

      // Click event for Author tab
      $('.author').click(function () {
        $(this).addClass('active');
        $('.book').removeClass('active');
        $('.authors-details-section').show();
        $('.book-details-section').hide();
        $('.image-wrapper-section.author').show();
        $('.image-wrapper-section.book').hide();
      });
    });


  }
}
</script>
