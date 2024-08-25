---
id: home
blueprint: pages
title: Home
template: home
author: 0a8a6ea8-8ff6-4670-9d7c-cd9829e1795d
meta_title: 'Revolve 314 Digital - Expert Web Development & Digital Marketing Solutions'
meta_description: 'Looking for top-notch web development services? At Revolve 314 Digital, we specialize in creating custom, high-performance websites tailored to your business needs. Our expert team delivers innovative solutions, ensuring your site is not only visually stunning but also user-friendly and optimized for search engines. Transform your online presence with us today!. Elevate your online presence with our Concrete5 CMS web development services. At Revolve 314 Digital, we specialize in creating custom, user-friendly websites using Concrete5, offering tailored design, robust functionality, and SEO optimization. Our expert team ensures a seamless experience with intuitive content management and stunning, responsive designs. Transform your site with Concrete5 today!. Unlock the full potential of your online presence with our WordPress CMS web development services. At Revolve 314 Digital, we create custom, responsive websites using WordPress, ensuring seamless functionality and stunning design. From theme customization to plugin development and SEO optimization, our expert team delivers tailored solutions that elevate your brand and enhance user experience. Get started with WordPress today!'
meta_tags: 'web development, custom web design, responsive web development, website development services, eCommerce web development, SEO-friendly web design, front-end development, back-end development, full-stack development, professional web developers, web design company, digital solutions, website optimization, user experience design, web development Concrete5, Concrete5 CMS services, Concrete5 website design, custom Concrete5 themes, Concrete5 CMS development, Concrete5 web development solutions, Concrete5 site customization, Concrete5 SEO optimization, Concrete5 CMS experts, Concrete5 development company, Concrete5 web design services, Concrete5 user-friendly websites, Concrete5 eCommerce solutions, Concrete5 CMS support,WordPress web development, custom WordPress design, WordPress CMS services, WordPress theme development, WordPress plugin development, responsive WordPress websites, SEO-friendly WordPress design, WordPress site optimization, WordPress development company, professional WordPress developers, WordPress eCommerce solutions, WordPress website support, WordPress site customization, WordPress web design services'
updated_by: 0a8a6ea8-8ff6-4670-9d7c-cd9829e1795d
updated_at: 1724561002
short_description: 'Stay ahead of the curve with our e-commerce/cms blog, featuring expert insights, industry trends, and actionable tips to drive online success. From website optimization to marketing strategies, our blog is your go-to resource for e-commerce expertise and inspiration to take your business to the next level.'
content:
  -
    type: set
    attrs:
      id: m07r2vqs
      values:
        type: home_gallery
        title_1: 'Unlocking the Power of the Web: Development Strategies and Trends'
        title_2: 'Image of a creative team develop websites using Concrete5 and WordPress'
        gallery_image: img/hero-bg.jpeg
        template: |-
          <!-- Hero Section -->
              <section id="hero" class="hero section dark-background">

                  <img src="{{gallery_image}}" alt="{{title_1}}" data-aos="fade-in">
            
                  <div class="container">
                    <div class="row">
                      <div class="col-lg-10">
                        <h2 data-aos="fade-up" data-aos-delay="100">{{title_1}}</h2>
                        <p data-aos="fade-up" data-aos-delay="200">{{title_2}}</p>
                       
                      </div>
                      <!--<div class="col-lg-5" data-aos="fade-up" data-aos-delay="300">
                        <form action="forms/newsletter.php" method="post" class="php-email-form">
                          <div class="sign-up-form"><input type="email" name="email"><input type="submit" value="Subscribe"></div>
                          <div class="loading">Loading</div>
                          <div class="error-message"></div>
                          <div class="sent-message">Your subscription request has been sent. Thank you!</div>
                        </form>
                      </div>-->
                    </div>
                  </div>
            
                </section><!-- /Hero Section -->
        edit_template: false
  -
    type: set
    attrs:
      id: m07rb1ks
      values:
        type: companies_work_with
        companies_work_with:
          - img/clients/client-1.png
          - img/clients/client-2.png
          - img/clients/client-3.png
          - img/clients/client-4.png
          - img/clients/client-5.png
          - img/clients/client-6.png
        template: |-
          <!-- Clients Section -->
              <section id="clients" class="clients section">

                <div class="container">

                  <div class="row gy-4">

                      {{companies_work_with}}

                    <div class="col-xl-2 col-md-3 col-6 client-logo">
                      <img src="{{ url }}" alt="{{ alt }}" />
                    </div><!-- End Client Item -->
                    {{/companies_work_with}}

                  </div>

                </div>

              </section><!-- /Clients Section -->
        edit_template: false
  -
    type: set
    attrs:
      id: m07rgpl0
      values:
        type: about_us_section
        about_us_image: img/about-us.jpeg
        title_1: 'About Us'
        title_2: 'Transforming Ideas into Digital Reality'
        description: "At Revolve 314 Digital, we're passionate about crafting innovative digital solutions that drive success for our clients. Our team of expert web developers, designers, and strategists work together to create bespoke websites and applications that exceed expectations."
        button_text: 'Read More'
        button_link: '#services'
        our_points:
          -
            id: m07s0ifn
            icon: '<i class="bi bi-buildings"></i>'
            title: 'Our Story'
            description: "Founded on the principles of creativity, collaboration, and technical excellence, Revolve 314 Digital has been helping businesses thrive online since 2010. Our name reflects our mission: to revolve around our clients' needs, providing tailored solutions that propel their growth."
            type: new_set
            enabled: true
          -
            id: m07s1sfb
            icon: '<i class="bi bi-clipboard-pulse"></i>'
            title: 'Our Expertise'
            description: 'With extensive experience in web development using WordPress, Concrete5, Statamic and Shopify, we deliver custom websites that are both visually stunning and functionally robust. Our expertise includes:'
            type: new_set
            enabled: true
          -
            id: m07s2zbz
            icon: '<i class="bi bi-command"></i>'
            title: 'Our Values'
            description: "Collaboration: We believe in working closely with our clients to understand their unique needs. - Innovation: We stay ahead of the curve, embracing the latest technologies and trends. - Quality: We strive for excellence in every project, delivering high-quality solutions that last. - Agility: We're adaptable and responsive, ensuring timely project delivery."
            type: new_set
            enabled: true
          -
            id: m07s4xom
            icon: '<i class="bi bi-graph-up-arrow"></i>'
            title: 'Get in Touch'
            description: 'Ready to elevate your online presence? Contact us today to explore how Revolve 314 Digital can help your business shine online.'
            type: new_set
            enabled: true
        template: |2-

              <!-- About Section -->
              <section id="about" class="about section light-background">

                <div class="container">
                  <div class="row align-items-xl-center gy-5">

                    <div class="col-xl-5 content">
          	          <img class="img-fluid" src="{{about_us_image}}"  alt="{{title_2}}">

                        <h3>{{title_1}}</h3>
                        <h2>{{title_2}}</h2>
                        <p>{{description}}</p>
                        <a href="{{button_link}}" class="read-more"><span>{{button_text}}</span><i class="bi bi-arrow-right"></i></a>
                    </div>

                    <div class="col-xl-7">
                      <div class="row gy-4 icon-boxes">

                          {{our_points}}
                          <div class="col-md-6" data-aos="fade-up" data-aos-delay="200">
                            <div class="icon-box">
                              {{icon}}
                              <h3>{{title}}</h3>
                              <p>{{description}}
            </p>
                            </div>
                          </div> <!-- End Icon Box -->
                          {{/our_points}}

                      </div>
                    </div>

                  </div>
                </div>

              </section><!-- /About Section -->
        edit_template: false
  -
    type: set
    attrs:
      id: m07sgze4
      values:
        type: statistics
        background_image: img/stats-bg.jpeg
        statistics:
          -
            id: m07shg1o
            number: '50'
            text: Clients
            type: new_set
            enabled: true
          -
            id: m07shne9
            number: '1000'
            text: Projects
            type: new_set
            enabled: true
          -
            id: m07shtvo
            number: '2000'
            text: 'Hours Of Support'
            type: new_set
            enabled: true
          -
            id: m07si7v6
            number: '35'
            text: Workers
            type: new_set
            enabled: true
        template: |-
          <!-- Stats Section -->
              <section id="stats" class="stats section dark-background">

                <img src="{{background_image}}" alt="" >

                <div class="container position-relative" data-aos="fade-up" data-aos-delay="100">

                  <div class="row gy-4">
                      {{statistics}}
                    <div class="col-lg-3 col-md-6">
                      <div class="stats-item text-center w-100 h-100">
                        <span data-purecounter-start="0" data-purecounter-end="{{number}}" data-purecounter-duration="1" class="purecounter"></span>
                        <p>+ {{text}}</p>
                      </div>
                    </div><!-- End Stats Item -->
                    {{/statistics}}
                

                  </div>

                </div>

              </section><!-- /Stats Section -->
        edit_template: false
  -
    type: set
    attrs:
      id: m07uogj1
      values:
        type: services
        title: Services
        description: 'Expert Web Development Services: Custom Solutions, Responsive Design, E-commerce Integration, Web Applications, and Ongoing Support. Transform Your Online Presence with Our Innovative Approach, Technical Expertise, and Collaborative Spirit. Elevate Your Business with Our Comprehensive Web Development Services'
        template: |-
          <!-- Services Section -->
            <section id="services" class="services section">

              <!-- Section Title -->
              <div class="container section-title">
                <h2>{{title}}</h2>
                <p>{{description}}</p>
              </div><!-- End Section Title -->

              <div class="container">

                <div class="row gy-4">

                    {{ collection from="services" }}

                  <div class="col-lg-6 ">
                    <div class="service-item d-flex">
                      <div class="icon flex-shrink-0">{{icon}}</div>
                      <div>
                        <h4 class="title"><a href="{{url}}" class="stretched-link" title="{{title}}">{{title}}</a></h4>
                        <p class="description">{{content}}</p>
                      </div>
                    </div>
                  </div>
                  <!-- End Service Item -->
                   {{/collection}}

                

                </div>

              </div>

            </section><!-- /Services Section -->
        edit_template: false
  -
    type: set
    attrs:
      id: m07wh7ba
      values:
        type: features
        heading: Features
        description: 'Expert web development services: Custom solutions, responsive designs, e-commerce integration, CMS development, SEO optimization, mobile-friendly websites, secure coding, fast loading speeds, user-friendly interfaces, scalable solutions, reliable maintenance, and 24/7 support. Delivering high-quality, innovative web solutions that drive business growth and exceed client expectations.'
        features:
          -
            id: m07wha2s
            title: 'Technical Features'
            description:
              -
                type: paragraph
                content:
                  -
                    type: text
                    text: 'Cutting-edge technology solutions: Responsive web design, custom CMS development, e-commerce integration, secure coding practices, fast loading speeds, scalable architecture, SEO optimization, and cross-browser compatibility. Leveraging latest technologies and frameworks for robust, efficient, and high-performance web development, ensuring seamless user experiences and driving business growth.'
              -
                type: bulletList
                content:
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Responsive Web Design'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Custom CMS Development'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'E-commerce Integration'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Mobile-Friendly Websites'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Secure Coding Practices'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Fast Loading Speeds'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Scalable Solutions'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'SEO Optimization'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Cross-Browser Compatibility'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Reliable Maintenance'
            images: img/technical-features-1.jpeg
            type: new_set
            enabled: true
            featured_data:
              -
                type: paragraph
                content:
                  -
                    type: text
                    text: 'Cutting-edge technology solutions: Responsive web design, custom CMS development, e-commerce integration, secure coding practices, fast loading speeds, scalable architecture, SEO optimization, and cross-browser compatibility. Leveraging latest technologies and frameworks for robust, efficient, and high-performance web development, ensuring seamless user experiences and driving business growth.'
              -
                type: bulletList
                content:
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Responsive Web Design'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Custom CMS Development'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'E-commerce Integration'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Mobile-Friendly Websites'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Secure Coding Practices'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Fast Loading Speeds'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Scalable Solutions'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'SEO Optimization'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Cross-Browser Compatibility'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Reliable Maintenance'
          -
            id: m07wi9nz
            title: 'Design Features'
            description:
              -
                type: paragraph
                content:
                  -
                    type: text
                    text: 'Visually stunning designs: User-friendly interfaces, customizable templates, high-quality graphics, consistent branding, and intuitive navigation. Creating engaging user experiences through modern design principles, vibrant color schemes, and responsive layouts that adapt to all devices, ensuring a lasting impression and driving business success.'
              -
                type: bulletList
                content:
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'User-Friendly Interfaces'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Customizable Templates'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'High-Quality Graphics'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Consistent Branding'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Intuitive Navigation'
            images: img/design-feature.jpeg
            type: new_set
            enabled: true
            featured_data:
              -
                type: paragraph
                content:
                  -
                    type: text
                    text: 'Visually stunning designs: User-friendly interfaces, customizable templates, high-quality graphics, consistent branding, and intuitive navigation. Creating engaging user experiences through modern design principles, vibrant color schemes, and responsive layouts that adapt to all devices, ensuring a lasting impression and driving business success'
              -
                type: bulletList
                content:
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'User-Friendly Interfaces'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Customizable Templates'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'High-Quality Graphics'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Consistent Branding'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Intuitive Navigation'
          -
            id: m07wj26j
            title: 'Service Features'
            description:
              -
                type: paragraph
                content:
                  -
                    type: text
                    text: 'Exceptional service delivery: 24/7 support, expert consultation, timely project delivery, budget-friendly solutions, continuous improvement, client-centric approach, transparent communication, regular updates, quality assurance, and customer satisfaction guarantee. Fostering long-term relationships through reliable, flexible, and customer-focused services that exceed expectations and drive business growth.'
              -
                type: bulletList
                content:
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: '24/7 Support'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Expert Consultation'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Timely Project Delivery'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Budget-Friendly Solutions'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Continuous Improvement'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Client-Centric Approach'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Transparent Communication'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Regular Updates'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Quality Assurance'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Customer Satisfaction Guarantee'
            images: img/service-feature-1.jpeg
            type: new_set
            enabled: true
            featured_data:
              -
                type: paragraph
                content:
                  -
                    type: text
                    text: 'Exceptional service delivery: 24/7 support, expert consultation, timely project delivery, budget-friendly solutions, continuous improvement, client-centric approach, transparent communication, regular updates, quality assurance, and customer satisfaction guarantee. Fostering long-term relationships through reliable, flexible, and customer-focused services that exceed expectations and drive business growth.'
              -
                type: bulletList
                content:
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: '24/7 Support'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Expert Consultation'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Timely Project Delivery'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Budget-Friendly Solutions'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Continuous Improvement'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Client-Centric Approach'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Transparent Communication'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Regular Updates'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Quality Assurance'
                  -
                    type: listItem
                    content:
                      -
                        type: paragraph
                        content:
                          -
                            type: text
                            text: 'Customer Satisfaction Guarantee'
        template: |2-
           <!-- Features Section -->
              <section id="features" class="features section">

                <!-- Section Title -->
                <div class="container section-title">
                  <h2>{{heading}}</h2>
                  <p>{{description}}</p>
                </div><!-- End Section Title -->

                <div class="container">


                  {{features}}

                  {{if increment % 3 }}


                  <div class="row gy-4 align-items-center features-item">
                      <div class="col-lg-5 order-2 order-lg-1" data-aos="fade-up" data-aos-delay="200">
                        <h3>{{title}}</h3>
                        {{featured_data}}
                        
                      </div>
                      <div class="col-lg-7 order-1 order-lg-2 d-flex align-items-center" data-aos="zoom-out" data-aos-delay="100">
                           {{images}}
                          <img src="{{images}}" alt="" class="stack-front">
                          {{/images}}
                        
                      </div>
                    </div><!-- Features Item -->

                    {{else}}
                    <div class="row gy-4 align-items-stretch justify-content-between features-item ">
                      <div class="col-lg-6 d-flex align-items-center features-img-bg" data-aos="zoom-out">
                         {{images}}
                          <img src="{{images}}" alt="" class="stack-front">
                          {{/images}}
                      </div>
                      <div class="col-lg-5 d-flex justify-content-center flex-column" data-aos="fade-up">
                        <h3>{{title}}</h3>
                        {{featured_data}}
                       
                      </div>
                    </div><!-- Features Item -->
                   {{/if}}

                  {{/features}}
             </div>

              </section><!-- /Features Section -->
        edit_template: false
  -
    type: set
    attrs:
      id: m0807mpo
      values:
        type: portfolio
        section_title: Portfolio
        description: "Projects We've Loved: Web Development at Its Best"
        portfolio_items:
          -
            id: m0807ymr
            portfolio_category: wordpress
            image:
              - img/masonry-portfolio/Home-FCA-Ingeniería.png
              - img/masonry-portfolio/Kenneth-Smit.png
              - img/masonry-portfolio/QuadriBot.png
              - img/masonry-portfolio/Adrian-Bank.png
              - img/masonry-portfolio/Netphiles.png
              - img/masonry-portfolio/Salvador.png
              - img/masonry-portfolio/Chea.png
              - img/masonry-portfolio/Rainbow.png
              - img/masonry-portfolio/Olse-Polska.png
            type: new_set
            enabled: true
          -
            id: m080b6ck
            portfolio_category: concrete
            image:
              - img/masonry-portfolio/Bridges-MN.png
              - img/masonry-portfolio/Cartwrite.png
              - img/masonry-portfolio/Addex-Group.png
              - img/masonry-portfolio/Arcitile.png
              - img/masonry-portfolio/MAXVAC.png
              - img/masonry-portfolio/Diane-Hassall.png
            type: new_set
            enabled: true
          -
            id: m080cqro
            portfolio_category: statamic
            image:
              - img/masonry-portfolio/versacommerce.png
              - img/masonry-portfolio/kwan.png
              - img/masonry-portfolio/invoicexpress.png
              - img/masonry-portfolio/prairieblue.png
              - img/masonry-portfolio/okonu.png
            type: new_set
            enabled: true
          -
            id: m080dvbb
            portfolio_category: shopify
            image:
              - img/masonry-portfolio/Seattle-Seahawks.png
              - img/masonry-portfolio/SHOWTIME.png
              - img/masonry-portfolio/Stereogum.png
              - img/masonry-portfolio/Shop-Justice.png
              - img/masonry-portfolio/Luxury.png
              - img/masonry-portfolio/SAVEUR.png
            type: new_set
            enabled: true
        template: |2-
              <!-- Portfolio Section -->
              <section id="portfolio" class="portfolio section">

                <!-- Section Title -->
                <div class="container section-title">
                  <h2>{{section_title}}</h2>
                  <p>{{description}}</p>
                </div><!-- End Section Title -->

                <div class="container">

                  <div class="isotope-layout" data-default-filter="*" data-layout="masonry" data-sort="original-order">

                    <ul class="portfolio-filters isotope-filters" data-aos="fade-up" data-aos-delay="100">
                      <li data-filter="*" class="filter-active">All</li>
                  {{portfolio_items}}
                  <li data-filter=".filter-{{portfolio_category}}">{{portfolio_category:label}}</li>
                  {{/portfolio_items}}
                    </ul><!-- End Portfolio Filters -->

                    <div class="row gy-4 isotope-container" data-aos="fade-up" data-aos-delay="200">

                     


                      {{portfolio_items}} 
                      {{image}}
                      <div class="col-lg-4 col-md-6 portfolio-item isotope-item filter-{{portfolio_category}}">
                              
                        <img src="{{url}}" class="img-fluid" alt="{{portfolio_category}}">
                        <div class="portfolio-info">
                          <h4>{{portfolio_category:label}}</h4>
                          
                          <a href="{{url}}" title="{{portfolio_category:label}}" data-gallery="portfolio-gallery-app" class="glightbox preview-link"><i class="bi bi-zoom-in"></i></a>
                         
                        </div>
                           
                      </div><!-- End Portfolio Item -->
                      {{/image}}
                      {{/portfolio_items}}



                    </div><!-- End Portfolio Container -->

                  </div>

                </div>

              </section><!-- /Portfolio Section -->
        edit_template: false
  -
    type: set
    attrs:
      id: m082pgwy
      values:
        type: faq
        title: '<span>Frequently Asked </span><strong>Questions</strong>'
        description: "At Revolve 314 Digital, we strive to deliver exceptional web development services. Here are some answers to common questions: Our services include website design, development, e-commerce integration, and maintenance. Typical project timelines range from 2-6 weeks. Yes, we use responsive design to ensure device compatibility. Ongoing maintenance and support are available. E-commerce solutions can be integrated into your website. Pricing varies depending on project scope, but we work within your budget. Our team has experience with various technologies and platforms. Case studies and references are available upon request. If you have further questions, please don't hesitate to contact us!"
        faqs:
          -
            id: m082pjk0
            question: '1. What services does your web development company offer?'
            answer: 'Our company offers a range of services including website design, development, e-commerce integration, responsive design, and maintenance.'
            type: new_set
            enabled: true
          -
            id: m082tqhy
            question: ' 2. How long does it take to develop a website?'
            answer: 'The time it takes to develop a website varies depending on the complexity of the project, but typically takes 2-6 weeks.'
            type: new_set
            enabled: true
          -
            id: m082ucqx
            question: '3. Do you use responsive design?'
            answer: 'Yes, we use responsive design to ensure that your website looks great on all devices.'
            type: new_set
            enabled: true
          -
            id: m082ut3x
            question: '4. Can you help with website maintenance?'
            answer: 'Yes, we offer ongoing maintenance and support to ensure your website stays up-to-date and secure.'
            type: new_set
            enabled: true
          -
            id: m082v7xx
            question: '5. Do you provide e-commerce solutions?'
            answer: 'Yes, we can integrate e-commerce functionality into your website.'
            type: new_set
            enabled: true
          -
            id: m082vn2q
            question: '5. How much does it cost to develop a website?'
            answer: 'The cost varies depending on the scope of the project, but we offer competitive pricing and can work within your budget.'
            type: new_set
            enabled: true
          -
            id: m082w1q4
            question: '5. Can you provide references or examples of previous work?'
            answer: 'Yes, we can provide case studies and references upon request.'
            type: new_set
            enabled: true
        template: |-
          <!-- Faq Section -->
              <section id="faq" class="faq section">

                <div class="container">

                  <div class="row gy-4">

                    <div class="col-lg-4">
                      <div class="content px-xl-5">
                        <h3>{{title}}</h3>
                        <p>
                         {{description}}
                        </p>
                      </div>
                    </div>

                    <div class="col-lg-8">

                      <div class="faq-container">
                        

                      {{faqs}}
                      <div class="faq-item  {{ if is_first }} faq-active {{/if}}">
                          <h3><!--<span class="num">{{increment}}.</span> --><span>{{question}}</span></h3>
                          <div class="faq-content">
                            <p>{{answer}}</p>
                          </div>
                          <i class="faq-toggle bi bi-chevron-right"></i>
                        </div><!-- End Faq item-->
                      {{/faqs}}


                        

                     

                      </div>

                    </div>
                  </div>

                </div>

              </section><!-- /Faq Section -->
        edit_template: false
  -
    type: set
    attrs:
      id: m0837ipo
      values:
        type: testimonials
        heading: 'What Our Clients Say'
        description: "Don't just take our word for it! Our clients rave about our web development services. Read what they have to say about their experience working with us. From stunning website designs to seamless e-commerce integrations, we deliver high-quality results that drive real success. Check out our testimonials below to see how we've helped businesses like yours thrive online."
        testimonials:
          -
            id: m0837ky6
            author_image: img/testimonials/testimonials-1.jpg
            author_name: 'Saul Goodman'
            author_designation: 'Ceo &amp; Founder'
            testimonial_data: |-
              Revolve 314 exceeded our expectations in developing our company website! Their team of experts delivered a stunning design, intuitive navigation, and seamless e-commerce integration. Their responsive design ensures our site looks great on all devices, and their ongoing support gives us peace of mind. We've seen a significant increase in online engagement and sales since launching our new site. [Company Name] truly understands the needs of their clients and delivers high-quality results. We highly recommend them for any web development project!
                                    
            type: new_set
            enabled: true
          -
            id: m0838mml
            author_image: img/testimonials/testimonials-2.jpg
            author_name: 'Sara Wilsson'
            author_designation: Designer
            testimonial_data: "We were blown away by the level of expertise and professionalism at Revolve 314. Their team took the time to understand our unique needs and goals, and delivered a custom website solution that exceeded our expectations. The new site has improved our online presence, increased engagement, and driven more sales. The Revolve 314 team is responsive, reliable, and truly committed to their clients' success. We couldn't be happier with the result and highly recommend them to anyone looking for top-notch web development services!"
            type: new_set
            enabled: true
          -
            id: m0839wuk
            author_image: img/testimonials/testimonials-3.jpg
            author_name: 'Jena Karlis'
            author_designation: 'Store Owner'
            testimonial_data: "Ratheesh exceeded our expectations with a stunning website that perfectly captures our brand! Their team's expertise, professionalism, and dedication to success impressed us. We've seen a significant increase in online engagement, sales, and customer satisfaction. Their ongoing support is invaluable. We highly recommend them for top-notch web development services!"
            type: new_set
            enabled: true
          -
            id: m083awf1
            author_image: img/testimonials/testimonials-4.jpg
            author_name: 'Matt Brandon'
            author_designation: Freelancer
            testimonial_data: 'Revolve delivered a stunning website that exceeded our expectations! Their expertise, professionalism, and commitment to success impressed us. We highly recommend them for top-notch web development services!'
            type: new_set
            enabled: true
          -
            id: m083c68q
            author_image: img/testimonials/testimonials-5.jpg
            author_name: 'John Larson'
            author_designation: Entrepreneur
            testimonial_data: "They exceeded our expectations with a stunning website that perfectly captures our brand! Their team's expertise, professionalism, and dedication to success impressed us. We've seen a significant increase in online engagement and sales. We highly recommend them for top-notch web development services!"
            type: new_set
            enabled: true
        template: |-
          <!-- Testimonials Section -->
              <section id="testimonials" class="testimonials section light-background">

                <div class="container">

                  <div class="row align-items-center">

                    <div class="col-lg-5 info">
                      <h3>{{heading}}</h3>
                      <p>{{description}}
                      </p>
                    </div>

                    <div class="col-lg-7" >

                      <div class="swiper init-swiper">
                        <script type="application/json" class="swiper-config">
                          {
                            "loop": true,
                            "speed": 600,
                            "autoplay": {
                              "delay": 5000
                            },
                            "slidesPerView": "auto",
                            "pagination": {
                              "el": ".swiper-pagination",
                              "type": "bullets",
                              "clickable": true
                            }
                          }
                        </script>
                        <div class="swiper-wrapper">

                          {{testimonials}}

                          <div class="swiper-slide">
                            <div class="testimonial-item">
                              <div class="d-flex">
                                <img src="{{author_image}}" class="testimonial-img flex-shrink-0" alt="">
                                <div>
                                  <h3>{{author_name}}</h3>
                                  <h4>{{author_designation}}</h4>
                                  <div class="stars">
                                    <i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i>
                                  </div>
                                </div>
                              </div>
                              <p>
                                <i class="bi bi-quote quote-icon-left"></i>
                                <span>
                                  {{testimonial_data}}
                                </span>
                                <i class="bi bi-quote quote-icon-right"></i>
                              </p>
                            </div>
                          </div><!-- End testimonial item -->

                          {{/testimonials}}

                        

                        </div>
                        <div class="swiper-pagination"></div>
                      </div>

                    </div>

                  </div>

                </div>

              </section><!-- /Testimonials Section -->
        edit_template: false
  -
    type: set
    attrs:
      id: m088narq
      values:
        type: blog_posts
        title: 'Recent Posts'
        description: 'Stay Up-to-Date with Our Latest Insights: Recent Blog Posts on Web Development, SEO, and Digital Marketing Trends and Best Practices.'
        number_of_posts: 3
        template: |-
          <!-- Recent Posts Section -->
              <section id="recent-posts" class="recent-posts section">

                <!-- Section Title -->
                <div class="container section-title">
                  <h2>{{title}}</h2>
                  <p>{{description}}</p>
                </div><!-- End Section Title -->

                <div class="container">

                  <div class="row gy-4">
          	         {{ collection:blog limit="3" as="posts"  sort="date_created:desc" }}

          {{ posts }}
                    <div class="col-xl-4 col-md-6" >
                      <article>

                        <div class="post-img">
                          <img src="{{image}}" alt="{{title}}" class="img-fluid">
                        </div>

                        <p class="post-category">{{blog_category:label}}</p>

                        <h2 class="title">
                          <a href="{{url}}">{{title}}</a>
                        </h2>

                        <div class="d-flex align-items-center">
                          
                          <div class="post-meta">
                           
                            <p class="post-date">
                              <time>{{date_created}}</time>
                            </p>
                          </div>
                        </div>

                      </article>
                    </div><!-- End post list item -->
                    {{ /posts }}

          {{/collection:blog}}
                   

                  </div><!-- End recent posts list -->

                </div>

              </section><!-- /Recent Posts Section -->
        edit_template: false
  -
    type: set
    attrs:
      id: m08alxtl
      values:
        type: contact_us
        section_title: Contact
        description: 'Contact Our Web Development Team for Your Project Inquiries, Support, and Feedback Anytime, Anywhere'
        location_map: '<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d31562.565722108287!2d76.8473307567247!3d8.565127841926492!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3b05be54c4adee2d%3A0x6367a27de8baa463!2sKazhakkoottam%2C%20Kerala!5e0!3m2!1sen!2sin!4v1723823556428!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>'
        contact_details:
          -
            id: m08am0kt
            icon: '<i class="bi bi-telephone"></i>'
            title: 'Call Us'
            data:
              -
                type: paragraph
                content:
                  -
                    type: text
                    marks:
                      -
                        type: link
                        attrs:
                          href: 'tel:+918907289865'
                          rel: null
                          target: null
                          title: null
                    text: '+918907289865'
            type: new_set
            enabled: true
          -
            id: m08ambgw
            icon: '<i class="bi bi-envelope"></i>'
            title: 'Email Us'
            data:
              -
                type: paragraph
                content:
                  -
                    type: text
                    marks:
                      -
                        type: link
                        attrs:
                          href: 'mailto:manup.rav@gmail.com'
                          rel: null
                          target: null
                          title: null
                    text: manup.rav@gmail.com
            type: new_set
            enabled: true
          -
            id: m08amz49
            icon: '<i class="bi bi-clock"></i>'
            title: 'Open Hours'
            data:
              -
                type: paragraph
                content:
                  -
                    type: text
                    text: 'Monday - Friday'
              -
                type: paragraph
                content:
                  -
                    type: text
                    text: '9:00AM - 05:00PM'
            type: new_set
            enabled: true
        template: |-
          <!-- Contact Section -->
              <section id="contact" class="contact section">

                <!-- Section Title -->
                <div class="container section-title">
                  <h2>{{section_title}}</h2>
                  <p>{{description}}</p>
                </div><!-- End Section Title -->

                <div class="container">

                  <div class="row gy-4">

                    <div class="col-lg-6">

                      <div class="row gy-4">
                        
                        {{contact_details}}

                        <div class="col-md-6">
                          <div class="info-item">
                            {{icon}}
                            <h3>{{title}}</h3>
                            {{data}}
                            
                          </div>
                        </div><!-- End Info Item -->

                       
                        {{/contact_details}}

                      </div>

                    </div>

                    <div class="col-lg-6">
          	          {{location_map}}

                    </div><!-- End Contact Form -->

                  </div>

                </div>

              </section><!-- /Contact Section -->
        edit_template: false
---
