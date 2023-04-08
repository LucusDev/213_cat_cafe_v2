<script>
</script>

<svelte:head>
  <title>Home</title>
  <meta name="description" content="Svelte demo app" />
</svelte:head>
<div class="container-xxl bg-white p-0">
  <!-- Navbar & Hero Start -->
  <!-- <div class="container-xxl position-relative p-0"> -->
  <div class="container-xxl py-5 bg-dark mb-5">
    <!-- <div class="container my-5 py-5"> -->
    <div class="row align-items-center g-5 px-5">
      <div class="col-lg-6 text-center text-lg-start">
        <h1 class="display-3 text-white animated slideInLeft">
          Come for the Coffee<br /> Stay for the Cats
        </h1>
        <p class="text-white animated slideInLeft mb-4 pb-2">
          Welcome to Mori, your ultimate cat cafe experience! We're more than
          just a cafe; we're a safe haven for cats when their owners need a
          helping hand. With our cat pick-up service, we make sure your cat is
          happy and cared for while you're away. Our cozy cafe is the perfect
          place to relax, sip on coffee, and cuddle with our friendly cats. Come
          visit us at Mori, where coffee and cats go paw-in-paw.
        </p>
        <a href="booking" class="btn btn-primary py-sm-3 px-sm-5 my-1"
          >Book A Table</a
        >
        <span class=" me-3 ms-3 text-white">or</span>
        <a href="booking" class="btn btn-primary py-sm-3 px-sm-5 my-1"
          >Pick up my cat</a
        >
      </div>
      <div class="col-lg-6 text-center text-lg-end overflow-hidden">
        <img class="img-fluid rounded-circle" src="img/hero.png" alt="" />
      </div>
    </div>
    <!-- </div> -->
  </div>

  <!-- Navbar & Hero End -->

  <!-- Service Start -->
  <div class="container-xxl py-5">
    <div class="container">
      <div class="row g-3">
        <div class="col-lg-3 col-sm-6" data-wow-delay="0.3s">
          <a href="service#relax-cafe">
            <div class="service-item rounded pt-3">
              <div class="p-4">
                <i class="fa fa-3x fa-mug-hot text-primary mb-4" />
                <h5>Relaxing Cafe</h5>
                <p class="text-black-50">
                  Step into our relaxing cafe and leave your troubles behind. No
                  matter how rough or tired you may be, our space will transport
                  you to a world of tranquility and peace.
                </p>
              </div>
            </div>
          </a>
        </div>

        <div class="col-lg-3 col-sm-6" data-wow-delay="0.3s">
          <a href="service#cat-pick-up">
            <div class="service-item rounded pt-3">
              <div class="p-4">
                <i class="fa fa-3x fa-truck-pickup text-primary mb-4" />
                <h5>Cat Pick-Up Service</h5>
                <p class="text-black-50">
                  We can come and pick up your cat and take care of it for you
                  for a small fee.
                </p>
              </div>
            </div>
          </a>
        </div>

        <div class="col-lg-3 col-sm-6" data-wow-delay="0.5s">
          <a href="service#cat-sit">
            <div class="service-item rounded pt-3">
              <div class="p-4">
                <i class="fa fa-3x fa-paw text-primary mb-4" />
                <h5>Cat Sitting Service</h5>
                <p class="text-black-50">
                  If you are having a busy day and want someone to take care of
                  your cats, you can drop off at our cafe for free.
                </p>
              </div>
            </div>
          </a>
        </div>
        <div class="col-lg-3 col-sm-6" data-wow-delay="0.7s">
          <a href="service#cat-groom">
            <div class="service-item rounded pt-3">
              <div class="p-4">
                <i class="fa fa-3x fa-headset text-primary mb-4" />
                <h5>Cat grooming services</h5>
                <p class="text-black-50">
                  We at Mori have some of the best people to ensure your cat
                  friends look and feel their best.
                </p>
              </div>
            </div>
          </a>
        </div>
      </div>
    </div>
  </div>
  <!-- Service End -->

  <!-- About Start -->
  <div class="container-xxl py-5">
    <div class="container">
      <div class="row g-5 align-items-center">
        <div class="col-lg-6">
          <div class="row g-3">
            <div class="col-6 text-start">
              <img
                class="img-fluid rounded w-100 wow zoomIn"
                data-wow-delay="0.1s"
                src="img/about-1.jpg"
              />
            </div>
            <div class="col-6 text-start">
              <img
                class="img-fluid rounded w-75 wow zoomIn"
                data-wow-delay="0.3s"
                src="img/about-2.jpg"
                style="margin-top: 25%;"
              />
            </div>
            <div class="col-6 text-end">
              <img
                class="img-fluid rounded w-75 wow zoomIn"
                data-wow-delay="0.5s"
                src="img/about-3.jpg"
              />
            </div>
            <div class="col-6 text-end">
              <img
                class="img-fluid rounded w-100 wow zoomIn"
                data-wow-delay="0.7s"
                src="img/about-4.jpg"
              />
            </div>
          </div>
        </div>
        <div class="col-lg-6">
          <h5
            class="section-title ff-secondary text-start text-primary fw-normal"
          >
            About Us
          </h5>
          <h1 class="mb-4">Welcome to Mori</h1>
          <p class="mb-4">
            Welcome to Mori, the cat cafe of your dreams! Our cozy cafe is a
            sanctuary for cat lovers and cats alike. Come cuddle with our
            playful cats while sipping on your favorite coffee or tea. Our
            mission is to provide a relaxing and stress-free environment for
            both cats and humans. Come visit us at Mori and experience the magic
            of coffee and cats!
          </p>
          <p class="mb-4">
            Our cat pick-up service is designed to help busy cat owners by
            providing a safe and caring environment for their cat friends when
            they're unable to take care of them themselves. We carefully select
            friendly and playful cats from our cafe and transport them to our
            facility where they receive the attention and care they deserve. Our
            cat pick-up service gives cat owners peace of mind, knowing their
            pets are in good hands.
          </p>
          <!-- <div class="row g-4 mb-4">
						<div class="col-sm-6">
							<div class="d-flex align-items-center border-start border-5 border-primary px-3">
								<h1 class="flex-shrink-0 display-5 text-primary mb-0" data-toggle="counter-up">15
								</h1>
								<div class="ps-4">
									<p class="mb-0">Years of</p>
									<h6 class="text-uppercase mb-0">Experience</h6>
								</div>
							</div>
						</div>
						<div class="col-sm-6">
							<div class="d-flex align-items-center border-start border-5 border-primary px-3">
								<h1 class="flex-shrink-0 display-5 text-primary mb-0" data-toggle="counter-up">50
								</h1>
								<div class="ps-4">
									<p class="mb-0">Popular</p>
									<h6 class="text-uppercase mb-0">Master Chefs</h6>
								</div>
							</div>
						</div>
					</div> -->
          <a class="btn btn-primary py-3 px-5 mt-2" href="about">Read More</a>
        </div>
      </div>
    </div>
  </div>
  <!-- About End -->

  <!-- Menu Start -->
  <div class="container-xxl py-5">
    <div class="container">
      <div class="text-center" data-wow-delay="0.1s">
        <h5
          class="section-title ff-secondary text-center text-primary fw-normal"
        >
          Cafe Menu
        </h5>
        <!-- <h1 class="mb-5">Most Popular Items</h1> -->
      </div>
      <div class="tab-class text-center" data-wow-delay="0.1s">
        <ul
          class="nav nav-pills d-inline-flex justify-content-center border-bottom mb-5"
        >
          <li class="nav-item">
            <a
              class="d-flex align-items-center text-start mx-3 ms-0 pb-3 active"
              data-bs-toggle="pill"
              href="#tab-1"
            >
              <i class="fa fa-coffee fa-2x text-primary" />
              <div class="ps-3">
                <small class="text-body">Popular</small>
                <h6 class="mt-n1 mb-0">Coffee & Tea</h6>
              </div>
            </a>
          </li>
          <li class="nav-item">
            <a
              class="d-flex align-items-center text-start mx-3 pb-3"
              data-bs-toggle="pill"
              href="#tab-2"
            >
              <i class="fa fa-birthday-cake fa-2x text-primary" />
              <div class="ps-3">
                <small class="text-body">Popular</small>
                <h6 class="mt-n1 mb-0">Cake and Bread</h6>
              </div>
            </a>
          </li>
          <!-- <li class="nav-item">
						<a class="d-flex align-items-center text-start mx-3 me-0 pb-3" data-bs-toggle="pill"
							href="#tab-3">
							<i class="fa fa-utensils fa-2x text-primary"></i>
							<div class="ps-3">
								<small class="text-body">Lovely</small>
								<h6 class="mt-n1 mb-0">Dinner</h6>
							</div>
						</a>
					</li> -->
        </ul>
        <div class="tab-content">
          <div id="tab-1" class="tab-pane fade show p-0 active">
            <div class="row g-4">
              <div class="col-lg-6">
                <div class="d-flex align-items-center">
                  <img
                    class="flex-shrink-0 img-fluid rounded"
                    src="img/menu-1.jpg"
                    alt=""
                    style="width: 80px;"
                  />
                  <div class="w-100 d-flex flex-column text-start ps-4">
                    <h5
                      class="d-flex justify-content-between border-bottom pb-2"
                    >
                      <span>Drip Coffee</span>
                      <span class="text-primary">฿115</span>
                    </h5>
                    <small class="fst-italic"
                      >This classic option has a bold, robust flavor and is a
                      great choice for coffee lovers who prefer a simple cup of
                      coffee. It can be served black or customized with cream
                      and sugar to taste.</small
                    >
                  </div>
                </div>
              </div>
              <div class="col-lg-6">
                <div class="d-flex align-items-center">
                  <img
                    class="flex-shrink-0 img-fluid rounded"
                    src="img/menu-2.jpg"
                    alt=""
                    style="width: 80px;"
                  />
                  <div class="w-100 d-flex flex-column text-start ps-4">
                    <h5
                      class="d-flex justify-content-between border-bottom pb-2"
                    >
                      <span>Espresso</span>
                      <span class="text-primary">฿130</span>
                    </h5>
                    <small class="fst-italic"
                      >This concentrated shot of coffee has a strong, rich
                      flavor that is best enjoyed on its own. However, it can
                      also be used as a base for other coffee drinks like
                      cappuccinos and lattes.</small
                    >
                  </div>
                </div>
              </div>
              <div class="col-lg-6">
                <div class="d-flex align-items-center">
                  <img
                    class="flex-shrink-0 img-fluid rounded"
                    src="img/menu-3.jpg"
                    alt=""
                    style="width: 80px;"
                  />
                  <div class="w-100 d-flex flex-column text-start ps-4">
                    <h5
                      class="d-flex justify-content-between border-bottom pb-2"
                    >
                      <span>Cappuccino</span>
                      <span class="text-primary">฿150</span>
                    </h5>
                    <small class="fst-italic"
                      >A popular Italian coffee drink, cappuccinos have a
                      creamy, rich taste with a layer of foam on top. They are
                      typically made with equal parts espresso, steamed milk,
                      and frothed milk.</small
                    >
                  </div>
                </div>
              </div>
              <div class="col-lg-6">
                <div class="d-flex align-items-center">
                  <img
                    class="flex-shrink-0 img-fluid rounded"
                    src="img/menu-4.jpg"
                    alt=""
                    style="width: 80px;"
                  />
                  <div class="w-100 d-flex flex-column text-start ps-4">
                    <h5
                      class="d-flex justify-content-between border-bottom pb-2"
                    >
                      <span>Latte</span>
                      <span class="text-primary">฿150</span>
                    </h5>
                    <small class="fst-italic"
                      >Lattes have a creamy, smooth taste that is less strong
                      than a straight espresso. They are made with espresso,
                      steamed milk, and a small layer of foam on top. Flavor
                      syrups can also be added to customize the taste.</small
                    >
                  </div>
                </div>
              </div>
              <div class="col-lg-6">
                <div class="d-flex align-items-center">
                  <img
                    class="flex-shrink-0 img-fluid rounded"
                    src="img/menu-5.jpg"
                    alt=""
                    style="width: 80px;"
                  />
                  <div class="w-100 d-flex flex-column text-start ps-4">
                    <h5
                      class="d-flex justify-content-between border-bottom pb-2"
                    >
                      <span>Black Tea</span>
                      <span class="text-primary">฿120</span>
                    </h5>
                    <small class="fst-italic"
                      >A classic tea option, black tea has a strong, bold flavor
                      and is often enjoyed with a splash of milk and sugar.</small
                    >
                  </div>
                </div>
              </div>
              <div class="col-lg-6">
                <div class="d-flex align-items-center">
                  <img
                    class="flex-shrink-0 img-fluid rounded"
                    src="img/menu-6.jpg"
                    alt=""
                    style="width: 80px;"
                  />
                  <div class="w-100 d-flex flex-column text-start ps-4">
                    <h5
                      class="d-flex justify-content-between border-bottom pb-2"
                    >
                      <span>Green Tea</span>
                      <span class="text-primary">฿160</span>
                    </h5>
                    <small class="fst-italic"
                      >A lighter, more delicate tea option, green tea has a
                      slightly sweet, earthy flavor and is often enjoyed plain
                      or with a small amount of honey.</small
                    >
                  </div>
                </div>
              </div>
              <div class="col-lg-6">
                <div class="d-flex align-items-center">
                  <img
                    class="flex-shrink-0 img-fluid rounded"
                    src="img/menu-7.jpg"
                    alt=""
                    style="width: 80px;"
                  />
                  <div class="w-100 d-flex flex-column text-start ps-4">
                    <h5
                      class="d-flex justify-content-between border-bottom pb-2"
                    >
                      <span>Herbal Tea</span>
                      <span class="text-primary">฿130</span>
                    </h5>
                    <small class="fst-italic"
                      >Made from a variety of herbs and spices, herbal teas have
                      a range of flavors and can be enjoyed hot or cold. Some
                      popular options include peppermint, chamomile, and ginger.</small
                    >
                  </div>
                </div>
              </div>
              <div class="col-lg-6">
                <div class="d-flex align-items-center">
                  <img
                    class="flex-shrink-0 img-fluid rounded"
                    src="img/menu-8.jpg"
                    alt=""
                    style="width: 80px;"
                  />
                  <div class="w-100 d-flex flex-column text-start ps-4">
                    <h5
                      class="d-flex justify-content-between border-bottom pb-2"
                    >
                      <span>Catnip Tea</span>
                      <span class="text-primary">฿115</span>
                    </h5>
                    <small class="fst-italic"
                      >A relaxing tea made with catnip leaves, which are known
                      to have calming effects on cats.</small
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div id="tab-2" class="tab-pane fade show p-0">
            <div class="row g-4">
              <div class="col-lg-6">
                <div class="d-flex align-items-center">
                  <img
                    class="flex-shrink-0 img-fluid rounded"
                    src="img/menu-9.jpg"
                    alt=""
                    style="width: 80px;"
                  />
                  <div class="w-100 d-flex flex-column text-start ps-4">
                    <h5
                      class="d-flex justify-content-between border-bottom pb-2"
                    >
                      <span>Kitty Cookies</span>
                      <span class="text-primary">฿70</span>
                    </h5>
                    <small class="fst-italic"
                      >Homemade cat-shaped cookies made with all-natural
                      ingredients, such as peanut butter, pumpkin, or catnip.</small
                    >
                  </div>
                </div>
              </div>
              <div class="col-lg-6">
                <div class="d-flex align-items-center">
                  <img
                    class="flex-shrink-0 img-fluid rounded"
                    src="img/menu-10.jpg"
                    alt=""
                    style="width: 80px;"
                  />
                  <div class="w-100 d-flex flex-column text-start ps-4">
                    <h5
                      class="d-flex justify-content-between border-bottom pb-2"
                    >
                      <span>Baguette</span>
                      <span class="text-primary">฿115</span>
                    </h5>
                    <small class="fst-italic"
                      >A classic bread option that is simple and versatile. It
                      can be served as is, toasted, or paired with various
                      spreads and toppings.</small
                    >
                  </div>
                </div>
              </div>
              <div class="col-lg-6">
                <div class="d-flex align-items-center">
                  <img
                    class="flex-shrink-0 img-fluid rounded"
                    src="img/menu-11.jpg"
                    alt=""
                    style="width: 80px;"
                  />
                  <div class="w-100 d-flex flex-column text-start ps-4">
                    <h5
                      class="d-flex justify-content-between border-bottom pb-2"
                    >
                      <span>Sourdough Bread</span>
                      <span class="text-primary">฿100</span>
                    </h5>
                    <small class="fst-italic"
                      >A classic bread with a slightly tangy flavor and chewy
                      texture. It can be served as is or paired with various
                      spreads and toppings, such as butter, jam, or avocado.</small
                    >
                  </div>
                </div>
              </div>
              <div class="col-lg-6">
                <div class="d-flex align-items-center">
                  <img
                    class="flex-shrink-0 img-fluid rounded"
                    src="img/menu-12.jpg"
                    alt=""
                    style="width: 80px;"
                  />
                  <div class="w-100 d-flex flex-column text-start ps-4">
                    <h5
                      class="d-flex justify-content-between border-bottom pb-2"
                    >
                      <span>Chocolate Cake</span>
                      <span class="text-primary">฿90</span>
                    </h5>
                    <small class="fst-italic"
                      >A rich and decadent cake that is always a crowd pleaser.
                      It can be served with various toppings, such as whipped
                      cream, chocolate ganache, or fresh berries.</small
                    >
                  </div>
                </div>
              </div>
              <div class="col-lg-6">
                <div class="d-flex align-items-center">
                  <img
                    class="flex-shrink-0 img-fluid rounded"
                    src="img/menu-13.jpg"
                    alt=""
                    style="width: 80px;"
                  />
                  <div class="w-100 d-flex flex-column text-start ps-4">
                    <h5
                      class="d-flex justify-content-between border-bottom pb-2"
                    >
                      <span>Lemon Cake</span>
                      <span class="text-primary">฿90</span>
                    </h5>
                    <small class="fst-italic"
                      >A light and refreshing cake that is perfect for spring
                      and summer. It is typically made with lemon zest and juice
                      and can be served with a dusting of powdered sugar or a
                      lemon glaze.</small
                    >
                  </div>
                </div>
              </div>
              <div class="col-lg-6">
                <div class="d-flex align-items-center">
                  <img
                    class="flex-shrink-0 img-fluid rounded"
                    src="img/menu-14.jpg"
                    alt=""
                    style="width: 80px;"
                  />
                  <div class="w-100 d-flex flex-column text-start ps-4">
                    <h5
                      class="d-flex justify-content-between border-bottom pb-2"
                    >
                      <span>Cheese Cake</span>
                      <span class="text-primary">฿100</span>
                    </h5>
                    <small class="fst-italic"
                      >A rich and creamy dessert made with cream cheese, eggs,
                      and sugar on a graham cracker crust. It is a timeless
                      favorite that can be served plain or with various
                      toppings, such as fruit compote or chocolate ganache.</small
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Menu End -->

  <!-- Reservation Start -->
  <div class="container-xxl py-5 px-0" data-wow-delay="0.1s">
    <div class="row g-0">
      <div class="col-md-6">
        <div class="video">
          <button
            type="button"
            class="btn-play"
            data-bs-toggle="modal"
            data-src="https://www.youtube.com/embed/h9cb1P7oxGU"
            data-bs-target="#videoModal"
          >
            <span />
          </button>
        </div>
      </div>
      <div class="col-md-6 bg-dark d-flex align-items-center">
        <div class="p-5" data-wow-delay="0.2s">
          <h5
            class="section-title ff-secondary text-start text-primary fw-normal"
          >
            Reservation
          </h5>
          <h1 class="text-white mb-4">Book A Table Online</h1>
          <form>
            <div class="row g-3">
              <div class="col-md-6">
                <div class="form-floating">
                  <input
                    type="text"
                    class="form-control"
                    id="name"
                    placeholder="Your Name"
                  />
                  <label for="name">Your Name</label>
                </div>
              </div>
              <div class="col-md-6">
                <div class="form-floating">
                  <input
                    type="email"
                    class="form-control"
                    id="email"
                    placeholder="Your Email"
                  />
                  <label for="email">Your Email</label>
                </div>
              </div>
              <div class="col-md-6">
                <div
                  class="form-floating date"
                  id="date3"
                  data-target-input="nearest"
                >
                  <input
                    type="text"
                    class="form-control datetimepicker-input"
                    id="datetime"
                    placeholder="Date & Time"
                    data-target="#date3"
                    data-toggle="datetimepicker"
                  />
                  <label for="datetime">Date & Time</label>
                </div>
              </div>
              <div class="col-md-6">
                <div class="form-floating">
                  <select class="form-select" id="select1">
                    <option value="1">People 1</option>
                    <option value="2">People 2</option>
                    <option value="3">People 3</option>
                  </select>
                  <label for="select1">No Of People</label>
                </div>
              </div>
              <div class="col-12">
                <div class="form-floating">
                  <textarea
                    class="form-control"
                    placeholder="Special Request"
                    id="message"
                    style="height: 100px"
                  />
                  <label for="message">Special Request</label>
                </div>
              </div>
              <div class="col-12">
                <button class="btn btn-primary w-100 py-3" type="submit"
                  >Book Now</button
                >
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>

  <div
    class="modal fade"
    id="videoModal"
    tabindex="-1"
    aria-labelledby="exampleModalLabel"
    aria-hidden="true"
  >
    <div class="modal-dialog">
      <div class="modal-content rounded-0">
        <div class="modal-header">
          <h5 class="modal-title" id="exampleModalLabel">Youtube Video</h5>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
          />
        </div>
        <div class="modal-body">
          <!-- 16:9 aspect ratio -->
          <div class="ratio ratio-16x9">
            <iframe
              class="embed-responsive-item"
              src=""
              id="video"
              allowfullscreen
              allow="autoplay"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Reservation Start -->

  <!-- Team Start -->
  <div class="container-xxl pt-5 pb-3">
    <div class="container">
      <div class="text-center" data-wow-delay="0.1s">
        <h5
          class="section-title ff-secondary text-center text-primary fw-normal"
        >
          Members
        </h5>
        <h1 class="mb-5">Our Cats</h1>
      </div>
      <div class="row g-4">
        <div class="col-lg-3 col-md-6" data-wow-delay="0.1s">
          <div class="team-item text-center rounded overflow-hidden">
            <div class="rounded-circle overflow-hidden m-4">
              <img class="img-fluid" src="img/team-1.jpg" alt="" />
            </div>
            <h5 class="mb-0">Beekin</h5>
            <small>Female</small><br />
            <small>2 years and 1 months</small>
            <div class="d-flex justify-content-center mt-3">
              <div class="d-flex justify-content-center mt-3">
                <a class="btn btn-square btn-primary mx-1" href="">></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6" data-wow-delay="0.3s">
          <div class="team-item text-center rounded overflow-hidden">
            <div class="rounded-circle overflow-hidden m-4">
              <img class="img-fluid" src="img/team-2.jpg" alt="" />
            </div>
            <h5 class="mb-0">Xoron</h5>
            <small>Female</small><br />
            <small>6 years and 11 months</small>
            <div class="d-flex justify-content-center mt-3">
              <div class="d-flex justify-content-center mt-3">
                <a class="btn btn-square btn-primary mx-1" href="">></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6" data-wow-delay="0.5s">
          <div class="team-item text-center rounded overflow-hidden">
            <div class="rounded-circle overflow-hidden m-4">
              <img class="img-fluid" src="img/team-3.jpeg" alt="" />
            </div>
            <h5 class="mb-0">Mazaki</h5>
            <small>Male</small><br />
            <small>7 years and 4 months</small>
            <div class="d-flex justify-content-center mt-3">
              <div class="d-flex justify-content-center mt-3">
                <a class="btn btn-square btn-primary mx-1" href="">></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6" data-wow-delay="0.7s">
          <div class="team-item text-center rounded overflow-hidden">
            <div class="rounded-circle overflow-hidden m-4">
              <img class="img-fluid" src="img/team-4.jpg" alt="" />
            </div>
            <h5 class="mb-0">Serumo</h5>
            <small>Male</small> <br />
            <small>5 years and 6 months</small>
            <div class="d-flex justify-content-center mt-3">
              <div class="d-flex justify-content-center mt-3">
                <a class="btn btn-square btn-primary mx-1" href="">></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Team End -->

  <!-- Testimonial Start -->
  <div class="container-xxl py-5" data-wow-delay="0.1s">
    <div class="container">
      <div class="text-center">
        <h5
          class="section-title ff-secondary text-center text-primary fw-normal"
        >
          Testimonial
        </h5>
        <h1 class="mb-5">Our Clients Say!!!</h1>
      </div>
      <div class="">
        <div class="testimonial-item bg-transparent border rounded p-4">
          <i class="fa fa-quote-left fa-2x text-primary mb-3" />
          <p>
            I recently visited Mori and was blown away by how cozy and welcoming
            the cafe was. The cats were so friendly and playful - it was the
            perfect escape from a stressful day. I highly recommend Mori to
            anyone looking for a relaxing and fun environment!
          </p>
          <div class="d-flex align-items-center">
            <img
              class="img-fluid flex-shrink-0 rounded-circle"
              src="img/testimonial-1.jpg"
              style="width: 50px; height: 50px;"
            />
            <div class="ps-3">
              <h5 class="mb-1">Emily</h5>
              <!-- <small>Profession</small> -->
            </div>
          </div>
        </div>
        <div class="testimonial-item bg-transparent border rounded p-4">
          <i class="fa fa-quote-left fa-2x text-primary mb-3" />
          <p>
            Mori's pick-up service is a lifesaver! With a busy schedule, it's
            hard to find time to take care of my cat. But with Mori, I know
            she's in great hands. The staff is friendly and professional, and
            the cafe is a wonderful place to relax with a cup of coffee and some
            cat friends.
          </p>
          <div class="d-flex align-items-center">
            <img
              class="img-fluid flex-shrink-0 rounded-circle"
              src="img/testimonial-2.jpg"
              style="width: 50px; height: 50px;"
            />
            <div class="ps-3">
              <h5 class="mb-1">Jane</h5>
              <!-- <small>Profession</small> -->
            </div>
          </div>
        </div>
        <div class="testimonial-item bg-transparent border rounded p-4">
          <i class="fa fa-quote-left fa-2x text-primary mb-3" />
          <p>
            I absolutely loved my experience at Mori! The cafe is cozy and
            inviting, and the cats are so sweet and playful. It's clear that the
            staff is passionate about what they do - they really care about the
            cats and making sure everyone has a great time. I will definitely be
            back!
          </p>
          <div class="d-flex align-items-center">
            <img
              class="img-fluid flex-shrink-0 rounded-circle"
              src="img/testimonial-3.jpg"
              style="width: 50px; height: 50px;"
            />
            <div class="ps-3">
              <h5 class="mb-1">Jack</h5>
              <!-- <small>Profession</small> -->
            </div>
          </div>
        </div>
        <div class="testimonial-item bg-transparent border rounded p-4">
          <i class="fa fa-quote-left fa-2x text-primary mb-3" />
          <p>
            Mori is hands-down the best cat cafe I've ever visited. The cats are
            so well-cared for and the staff is amazing. They go above and beyond
            to make sure everyone has a great experience. I would recommend Mori
            to anyone looking for a fun and unique coffee shop experience!
          </p>
          <div class="d-flex align-items-center">
            <img
              class="img-fluid flex-shrink-0 rounded-circle"
              src="img/testimonial-4.jpg"
              style="width: 50px; height: 50px;"
            />
            <div class="ps-3">
              <h5 class="mb-1">Sophia</h5>
              <!-- <small>Profession</small> -->
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Testimonial End -->

  <!-- Footer Start -->

  <!-- Footer End -->

  <!-- Back to Top -->
  <a href="#" class="btn btn-lg btn-primary btn-lg-square back-to-top"
    ><i class="bi bi-arrow-up" /></a
  >
</div>
