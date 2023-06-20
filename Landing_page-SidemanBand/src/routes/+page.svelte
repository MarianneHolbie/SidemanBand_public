
<!-- nav bar -->
<div class=" bg-orange-50/80 sticky top-0  z-20">
    <div class="px-4 py-6 mx-auto lg:py-8 sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8">
      <div class="relative flex items-center justify-between lg:justify-center lg:space-x-16">
        <ul class="flex items-center hidden space-x-8 lg:flex">
          <li><a  href="#Home" aria-label="Our product" title="Our product" class="font-medium tracking-wide text-gray-800 transition-colors duration-200 hover:text-orange-accent-400">Home</a></li>
          <li><a href="#History" aria-label="Our product" title="Our product" class="font-medium tracking-wide text-gray-800 transition-colors duration-200 hover:text-orange-accent-400">History</a></li>
          <li><a href="#Technical_stack" aria-label="Product pricing" title="Product pricing" class="font-medium tracking-wide text-gray-800 transition-colors duration-200 hover:text-orange-accent-400">Technical Stack</a></li>
        </ul>
        <a href="/" aria-label="Company" title="Company" class="inline-flex items-center">
            <img src=".\images\SidemanBand_logo.png" alt="Logo de votre entreprise" class="inline-flex items-center lg:mx-auto" height="50px" width="50px" >
          <span class="ml-2 text-xl font-bold tracking-wide text-gray-800 uppercase">SidemanBand</span>
        </a>
        <ul class="flex items-center hidden space-x-8 lg:flex">
          <li><a href="#Features" aria-label="About us" title="About us" class="font-medium tracking-wide text-gray-800 transition-colors duration-200 hover:text-orange-accent-400">Some features</a></li>
          <li><a href="#About" aria-label="Sign in" title="Sign in" class="font-medium tracking-wide text-gray-800 transition-colors duration-200 hover:text-orange-accent-400">About</a></li>
          <!-- <li><a href="/" aria-label="Sign up" title="Sign up" class="font-medium tracking-wide text-gray-800 transition-colors duration-200 hover:text-orange-accent-400">Sign up</a></li> -->
        </ul>
        <!-- Mobile menu -->
        <div class="lg:hidden">
          <button aria-label="Open Menu" title="Open Menu" class="p-2 -mr-1 transition duration-200 rounded focus:outline-none focus:shadow-outline">
            <svg class="w-5 text-gray-600" viewBox="0 0 24 24">
              <path fill="currentColor" d="M23,13H1c-0.6,0-1-0.4-1-1s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,13,23,13z"></path>
              <path fill="currentColor" d="M23,6H1C0.4,6,0,5.6,0,5s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,6,23,6z"></path>
              <path fill="currentColor" d="M23,20H1c-0.6,0-1-0.4-1-1s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,20,23,20z"></path>
            </svg>
          </button>
          <!-- Mobile menu dropdown 
          <div class="absolute top-0 left-0 w-full">
            <div class="p-5 bg-white border rounded shadow-sm">
              <div class="flex items-center justify-between mb-4">
                <div>
                  <a href="/" aria-label="Company" title="Company" class="inline-flex items-center">
                    <svg class="w-8 text-deep-purple-accent-400" viewBox="0 0 24 24" stroke-linejoin="round" stroke-width="2" stroke-linecap="round" stroke-miterlimit="10" stroke="currentColor" fill="none">
                      <rect x="3" y="1" width="7" height="12"></rect>
                      <rect x="3" y="17" width="7" height="6"></rect>
                      <rect x="14" y="1" width="7" height="6"></rect>
                      <rect x="14" y="11" width="7" height="12"></rect>
                    </svg>
                    <span class="ml-2 text-xl font-bold tracking-wide text-gray-800 uppercase">Company</span>
                  </a>
                </div>
                <div>
                  <button aria-label="Close Menu" title="Close Menu" class="p-2 -mt-2 -mr-2 transition duration-200 rounded hover:bg-gray-200 focus:bg-gray-200 focus:outline-none focus:shadow-outline">
                    <svg class="w-5 text-gray-600" viewBox="0 0 24 24">
                      <path
                        fill="currentColor"
                        d="M19.7,4.3c-0.4-0.4-1-0.4-1.4,0L12,10.6L5.7,4.3c-0.4-0.4-1-0.4-1.4,0s-0.4,1,0,1.4l6.3,6.3l-6.3,6.3 c-0.4,0.4-0.4,1,0,1.4C4.5,19.9,4.7,20,5,20s0.5-0.1,0.7-0.3l6.3-6.3l6.3,6.3c0.2,0.2,0.5,0.3,0.7,0.3s0.5-0.1,0.7-0.3 c0.4-0.4,0.4-1,0-1.4L13.4,12l6.3-6.3C20.1,5.3,20.1,4.7,19.7,4.3z"
                      ></path>
                    </svg>
                  </button>
                </div>
              </div>
              <nav>
                <ul class="space-y-4">
                  <li><a href="/" aria-label="Our product" title="Our product" class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400">Product</a></li>
                  <li><a href="/" aria-label="Our product" title="Our product" class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400">Features</a></li>
                  <li><a href="/" aria-label="Product pricing" title="Product pricing" class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400">Pricing</a></li>
                  <li><a href="/" aria-label="About us" title="About us" class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400">About us</a></li>
                  <li><a href="/" aria-label="Sign in" title="Sign in" class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400">Sign in</a></li>
                  <li>
                    <a
                      href="/"
                      class="inline-flex items-center justify-center w-full h-12 px-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none"
                      aria-label="Sign up"
                      title="Sign up"
                    >
                      Sign up
                    </a>
                  </li>
                </ul>
              </nav>
            </div>
          </div>
          -->
        </div>
      </div>
    </div>
  </div>

  <!-- logo SidemanBand -->
  <div class="flex flex-col items-center justify-center h-screen bg-cover bg-center">
    <h1 class="text-7xl font-bold mb-8">
        <img src=".\images\SidemanBand_slogan.png" alt="logo + slogan"/>
    </h1>
    </div>

<!-- Home section -->
  <div class="relative flex flex-col-reverse py-16 lg:pt-0 lg:flex-col lg:pb-0 bg-white">
    <div class="inset-y-0 top-0 right-0 z-0 w-full max-w-xl px-4 mx-auto md:px-0 lg:pr-0 lg:mb-0 lg:mx-0 lg:w-7/12 lg:max-w-full lg:absolute xl:px-0">
      <svg class="absolute left-0 hidden h-full text-white transform -translate-x-1/2 lg:block" viewBox="0 0 100 100" fill="currentColor" preserveAspectRatio="none slice">
        <path d="M50 0H100L50 100H0L50 0Z"></path>
      </svg>
      <img
        class="object-cover w-full h-56 rounded shadow-lg lg:rounded-none lg:shadow-none md:h-96 lg:h-full"
        src="https://images.unsplash.com/photo-1570563567687-3fc34035ec01?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1170&q=80"
        alt=""
      />
    </div>
    <div id="Home" class="relative flex flex-col items-start w-full max-w-xl px-4 mx-auto md:px-0 lg:px-8 lg:max-w-screen-xl">
        <div class="mb-16 lg:my-40 lg:max-w-lg lg:pr-5">
            <p class="inline-block px-3 py-px mb-4 text-xs font-semibold tracking-wider text-white uppercase rounded-full bg-deep-purple-400">
            Brand new
            </p>
            <h2 class="mb-5 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none">
            Everything you<br class="hidden md:block" />
            can imagine
            <span class="inline-block text-deep-purple-accent-400">is real</span>
            </h2>
            <p class="pr-5 mb-5 text-base text-gray-700 md:text-lg">
                Finally, a tool that will make finding replacement musicians easier for you. No more playing the middleman or spending hours on the phone!
            </p>
            <div class="flex items-center">
            <a
                href="https://github.com/MarianneHolbie/SidemanBand_public"
                class="inline-flex items-center justify-center h-12 px-6 mr-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none"
            >
                Get started
            </a>
            
            </div>
        </div>
    </div>
  </div>

    <!-- History section -->
  <div id="History" class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
    <div class="grid max-w-2xl mx-auto">
        <div>
            <p class=" px-3 py-px mb-4 text-lg font-semibold tracking-wider text-white uppercase rounded-full bg-deep-purple-accent-200">
              History
            </p>
        </div>
      <div class="flex">
        <div class="flex flex-col items-center mr-6">
          <div class="w-px h-10 opacity-0 sm:h-full"></div>
            <div>
                <div class="flex items-center justify-center w-8 h-8 text-xs font-medium border rounded-full">
                1
                </div>
            </div>
          <div class="w-px h-full bg-gray-300"></div>
        </div>
        <div class="flex flex-col pb-6 sm:items-center sm:flex-row sm:pb-0">
          <div class="sm:mr-5">
            <div class="flex items-center justify-center w-16 h-16 my-3 rounded-full bg-indigo-50 sm:w-24 sm:h-24">
              <svg class="w-12 h-12 text-deep-purple-accent-400 sm:w-16 sm:h-16" stroke="currentColor" viewBox="0 0 52 52">
                <polygon stroke-width="3" stroke-linecap="round" stroke-linejoin="round" fill="none" points="29 13 14 29 25 29 23 39 38 23 27 23"></polygon>
              </svg>
            </div>
          </div>
          <div>
            <p class="text-xl font-semibold sm:text-base">Identify a need</p>
            <p class="text-sm text-gray-700">
                Building a project from scratch is a great experience, but it's even better 
                when it addresses a specific need. As a musician myself and co-founder of a 
                big band with 17 musicians, I frequently encounter the problem of finding replacements. 
                To date, I haven't found an application or website that caters to this need, so I decided to create one!
            </p>
          </div>
        </div>
      </div>

      <div class="flex">
        <div class="flex flex-col items-center mr-6">
          <div class="w-px h-10 bg-gray-300 sm:h-full"></div>
          <div>
            <div class="flex items-center justify-center w-8 h-8 text-xs font-medium border rounded-full">
              2
            </div>
          </div>
          <div class="w-px h-full bg-gray-300"></div>
        </div>
        <div class="flex flex-col pb-6 sm:items-center sm:flex-row sm:pb-0">
          <div class="sm:mr-5">
            <div class="flex items-center justify-center w-16 h-16 my-3 rounded-full bg-indigo-50 sm:w-24 sm:h-24">
              <svg class="w-12 h-12 text-deep-purple-accent-400 sm:w-16 sm:h-16" stroke="currentColor" viewBox="0 0 52 52">
                <polygon stroke-width="3" stroke-linecap="round" stroke-linejoin="round" fill="none" points="29 13 14 29 25 29 23 39 38 23 27 23"></polygon>
              </svg>
            </div>
          </div>
          <div>
            <p class="text-xl font-semibold sm:text-base">Meet the need</p>
            <p class="text-sm text-gray-700">
                Once the need is identified, it's essential to envision how the solution will be used. Who will use the solution? How? What are their requirements? Based on this, I started developing user stories.
            </p>
          </div>
        </div>
      </div>

      <div class="flex">
        <div class="flex flex-col items-center mr-6">
          <div class="w-px h-10 bg-gray-300 sm:h-full"></div>
          <div>
            <div class="flex items-center justify-center w-8 h-8 text-xs font-medium border rounded-full">
              3
            </div>
          </div>
          <div class="w-px h-full opacity-0"></div>
        </div>
        <div class="flex flex-col pb-6 sm:items-center sm:flex-row sm:pb-0">
          <div class="sm:mr-5">
            <div class="flex items-center justify-center w-16 h-16 my-3 rounded-full bg-indigo-50 sm:w-24 sm:h-24">
              <svg class="w-12 h-12 text-deep-purple-accent-400 sm:w-16 sm:h-16" stroke="currentColor" viewBox="0 0 52 52">
                <polygon stroke-width="3" stroke-linecap="round" stroke-linejoin="round" fill="none" points="29 13 14 29 25 29 23 39 38 23 27 23"></polygon>
              </svg>
            </div>
          </div>
          <div>
            <p class="text-xl font-semibold sm:text-base">Build an architecture</p>
            <p class="text-sm text-gray-700">
                As a relatively new player in the tech world, having started less than 9 months ago, I leveraged the skills I acquired during my projects at Holberton School. The plan involved developing a back-end consisting of an API, database, and web server, while also designing the front-end.
            </p>
          </div>
        </div>
      </div>

      <div class="flex">
        <div class="flex flex-col items-center mr-6">
          <div class="w-px h-10 bg-gray-300 sm:h-full"></div>
          <div>
            <div class="flex items-center justify-center w-8 h-8 text-xs font-medium border rounded-full">
              4
            </div>
          </div>
          <div class="w-px h-full opacity-0"></div>
        </div>
        <div class="flex flex-col pb-6 sm:items-center sm:flex-row sm:pb-0">
          <div class="sm:mr-5">
            <div class="flex items-center justify-center w-16 h-16 my-3 rounded-full bg-indigo-50 sm:w-24 sm:h-24">
              <svg class="w-12 h-12 text-deep-purple-accent-400 sm:w-16 sm:h-16" stroke="currentColor" viewBox="0 0 52 52">
                <polygon stroke-width="3" stroke-linecap="round" stroke-linejoin="round" fill="none" points="29 13 14 29 25 29 23 39 38 23 27 23"></polygon>
              </svg>
            </div>
          </div>
          <div>
            <p class="text-xl font-semibold sm:text-base">Technology choices</p>
            <p class="text-sm text-gray-700">
                Select known and/or recent technologies. I had previous experience with MySQL from previous projects 
                and wanted to deepen my understanding. On the front-end side, the discovery of Svelte and the rising 
                SvelteKit framework impressed me with their modularity and use of JavaScript. With the intention of 
                expanding the project in terms of team and collaboration, and to enhance my Docker skills, the project 
                was designed using Docker Compose with two images: one for the API and one for the database.
            </p>
          </div>
        </div>
      </div>

      <div class="flex">
        <div class="flex flex-col items-center mr-6">
          <div class="w-px h-10 bg-gray-300 sm:h-full"></div>
          <div>
            <div class="flex items-center justify-center w-8 h-8 text-xs font-medium border rounded-full">
              5
            </div>
          </div>
          <div class="w-px h-full opacity-0"></div>
        </div>
        <div class="flex flex-col pb-6 sm:items-center sm:flex-row sm:pb-0">
          <div class="sm:mr-5">
            <div class="flex items-center justify-center w-16 h-16 my-3 rounded-full bg-indigo-50 sm:w-24 sm:h-24">
              <svg class="w-12 h-12 text-deep-purple-accent-400 sm:w-16 sm:h-16" stroke="currentColor" viewBox="0 0 52 52">
                <polygon stroke-width="3" stroke-linecap="round" stroke-linejoin="round" fill="none" points="29 13 14 29 25 29 23 39 38 23 27 23"></polygon>
              </svg>
            </div>
          </div>
          <div>
            <p class="text-xl font-semibold sm:text-base">Design</p>
            <p class="text-sm text-gray-700">
                Intense 15 days were dedicated to developing a robust back-end, implementing
                 secure JWT authentication, and creating a secure database, all while ensuring
                 a visually appealing front-end design.
            </p>
          </div>
        </div>
      </div>

      <div class="flex">
        <div class="flex flex-col items-center mr-6">
          <div class="w-px h-10 bg-gray-300 sm:h-full"></div>
          <div>
            <div class="flex items-center justify-center w-8 h-8 text-xs font-medium border rounded-full">
             6
            </div>
          </div>
          <div class="w-px h-full opacity-0"></div>
        </div>
        <div class="flex flex-col pb-6 sm:items-center sm:flex-row sm:pb-0">
          <div class="sm:mr-5">
            <div class="flex items-center justify-center w-16 h-16 my-3 rounded-full bg-indigo-50 sm:w-24 sm:h-24">
              <svg class="w-12 h-12 text-deep-purple-accent-400 sm:w-16 sm:h-16" stroke="currentColor" viewBox="0 0 52 52">
                <polygon stroke-width="3" stroke-linecap="round" stroke-linejoin="round" fill="none" points="29 13 14 29 25 29 23 39 38 23 27 23"></polygon>
              </svg>
            </div>
          </div>
          <div>
            <p class="text-xl font-semibold sm:text-base">Never Stop</p>
            <p class="text-sm text-gray-700">
                This portfolio project is just the beginning of its long journey, I hope. I believe this solution is relevant and I aspire to develop it further for an operational release in the near future.
            </p>
          </div>
        </div>
      </div>

    </div>
  </div>

      <!-- Technical STACK section -->

  <div id="Technical_stack" class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
    <div class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12">
      <div>
        <p class="inline-block px-3 py-px mb-4 text-xs font-semibold tracking-wider text-teal-900 uppercase rounded-full bg-teal-accent-400">
          Technical STACK
        </p>
      </div>
      <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto">
        <span class="relative inline-block">
          <svg viewBox="0 0 52 24" fill="currentColor" class="absolute top-0 left-0 z-0 hidden w-32 -mt-8 -ml-20 text-deep-purple-800 lg:w-32 lg:-ml-28 lg:-mt-10 sm:block">
            <defs>
              <pattern id="d9d7687a-355f-4502-8ec4-7945db034688" x="0" y="0" width=".135" height=".30">
                <circle cx="1" cy="1" r=".7"></circle>
              </pattern>
            </defs>
            <rect fill="url(#d9d7687a-355f-4502-8ec4-7945db034688)" width="52" height="24"></rect>
          </svg>
          <span class="relative">The</span>
        </span>
        right ingredients for successful development !
      </h2>
      <p class="text-base text-gray-700 md:text-lg">
        The main technologies used in the project include:
      </p>
    </div>
    <div class="grid gap-5 mb-8 md:grid-cols-2 lg:grid-cols-3">
      <div class="p-5 duration-300 transform bg-white border rounded shadow-sm hover:-translate-y-2">
        <div class="flex items-center justify-center w-32 h-32 mb-4 rounded-full bg-indigo-50 ">
          <img src=".\images\docker_compose.png" alt="logo docker compose">
        </div>
        <h6 class="mb-2 font-semibold leading-5">Docker Compose</h6>
        <p class="text-sm text-gray-900">
            The big advantage of using Compose is I define my application stack in a file, keep it at the root of my project repo (it's now version controlled),
             and easily enable someone else to contribute to my project. Someone would only need to clone my repo and start the compose app.
             I separated my API image from my database image so that if any issues arise, I can replace only the problematic part.
        </p>
      </div>
      <div class="p-5 duration-300 transform bg-white border rounded shadow-sm hover:-translate-y-2">
        <div class="flex items-center justify-center w-32 h-32 mb-4 rounded-full bg-indigo-50">
            <img src=".\images\JWT.png" alt="logo JWT">
        </div>
        <h6 class="mb-2 font-semibold leading-5">Secure authentication</h6>
        <p class="text-sm text-gray-900">
            Instead of storing information on the server after authentication, JWT creates a JSON web token and encodes, 
            sterilizes, and adds a signature with a secret key that cannot be tampered with. This key is then sent back 
            to the browser. Each time a request is sent, it verifies and sends the response back.
        </p>
      </div>
      <div class="p-5 duration-300 transform bg-white border rounded shadow-sm hover:-translate-y-2">
        <div class="flex items-center justify-center w-32 h-32 mb-4 rounded-full bg-indigo-50">
            <img src=".\images\FastAPI.png" alt="logo fastAPI">
        </div>
        <h6 class="mb-2 font-semibold leading-5">FastAPI</h6>
        <p class="text-sm text-gray-900">
            With its impressive speed, simple API, and built-in documentation, FastAPI is an excellent
             choice for building high-performance APIs. Its use of Python's type hints for automatic 
             validation and serialization eliminates boilerplate code and makes development faster and easier.
        </p>
      </div>
      <div class="p-5 duration-300 transform bg-white border rounded shadow-sm hover:-translate-y-2">
        <div class="flex items-center justify-center w-32 h-32 mb-4 rounded-full bg-indigo-50">
            <img src=".\images\mySQL.png" alt="logo MySQL">
        </div>
        <h6 class="mb-2 font-semibold leading-5">MySQL</h6>
        <p class="text-sm text-gray-900">
            MySQL is the second ranking RDBMS solution in the world, according to DB Engines. Its users include a wide range of websites and applications, including household brands like Spotify, Netflix, Facebook and Booking.com
        </p>
      </div>
      <div class="p-5 duration-300 transform bg-white border rounded shadow-sm hover:-translate-y-2">
        <div class="flex items-center justify-center w-32 h-32 mb-4 rounded-full bg-indigo-50">
            <img src=".\images\Sveltekit.png" alt="logo SvelteKit">
        </div>
        <h6 class="mb-2 font-semibold leading-5">SvelteKit</h6>
        <p class="text-sm text-gray-900">
            <strong>FAST</strong>
            Powered by Svelte and Vite, speed is baked into every crevice: fast setup, fast dev, fast builds, fast page loads, fast navigation. Did we mention it's fast?
            <br>
            <strong>FUN</strong>
            No more wasted days figuring out bundler configuration, routing, SSR, CSP, TypeScript, deployment settings and all the other boring stuff. Code with joy.
            <br>
            <strong>FLEXIBLE</strong>
            SPA? MPA? SSR? SSG? Check. SvelteKit gives you the tools to succeed whatever it is you're building. And it runs wherever JavaScript does.
        </p>
      </div>
      <div class="p-5 duration-300 transform bg-white border rounded shadow-sm hover:-translate-y-2">
        <div class="flex items-center justify-center w-32 h-32 mb-4 rounded-full bg-indigo-50">
            <img src=".\images\Tailwind_CSS_Logo.png" alt="logo Tailwind">
        </div>
        <h6 class="mb-2 font-semibold leading-5">Tailwind CSS</h6>
        <p class="text-sm text-gray-900">
            Tailwind CSS makes it quicker to write and maintain the code of your application. 
            By using this utility-first framework, you don't have to write custom CSS to style your 
            application. Instead, you can use utility classes to control the padding, margin, color, 
            font, shadow, and more of your application.
        </p>
      </div>
    </div>
  </div>

  <!-- Screenshot section -->
  <div id="Features" class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
    <div class="flex flex-col mb-6 lg:justify-between lg:flex-row md:mb-8">
      <h2 class="max-w-lg mb-5 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none md:mb-6 group">
        <span class="inline-block mb-1 sm:mb-4">
          Some features<br class="hidden md:block" />
          
        </span>
        <div class="h-1 ml-auto duration-300 origin-left transform bg-deep-purple-accent-400 scale-x-30 group-hover:scale-x-100"></div>
      </h2>
      <p class="text-gray-700 lg:text-sm lg:max-w-md">
        The backend doesn't do it all! Design is of utmost importance.
        A simple design focused on meeting the users' needs for now.
      </p>
    </div>
    <div class="grid gap-6 row-gap-5 mb-8 lg:grid-cols-2 sm:row-gap-6 sm:grid-cols-2">
      <a href="/" aria-label="View Item">
        <div class="relative overflow-hidden transition duration-200 transform rounded shadow-lg hover:-translate-y-2 hover:shadow-2xl">
          <img class="object-cover w-full h-56 md:h-64 xl:h-80" src=".\images\Connexion.png?auto=compress&amp" alt="" />
          <div class="absolute inset-0 px-6 py-4 transition-opacity duration-200 bg-black bg-opacity-75 opacity-0 hover:opacity-100">
            <p class="mb-4 text-lg font-bold text-gray-100">Login page</p>
            <p class="text-sm tracking-wide text-gray-300">
                For registered users to log in.
            </p>
          </div>
        </div>
      </a>
      <a href="/" aria-label="View Item">
        <div class="relative overflow-hidden transition duration-200 transform rounded shadow-lg hover:-translate-y-2 hover:shadow-2xl">
          <img class="object-cover w-full h-56 md:h-64 xl:h-80" src=".\images\Dashboard_instru.png?auto=compress&amp" alt="" />
          <div class="absolute inset-0 px-6 py-4 transition-opacity duration-200 bg-black bg-opacity-75 opacity-0 hover:opacity-100">
            <p class="mb-4 text-lg font-bold text-gray-100">Dashboard page</p>
            <p class="text-sm tracking-wide text-gray-300">
                Once authenticated, the user has access to a dashboard where they can modify their information, add/remove their instruments, and indicate their availability.
            </p>
          </div>
        </div>
      </a>
      <a href="/" aria-label="View Item">
        <div class="relative overflow-hidden transition duration-200 transform rounded shadow-lg hover:-translate-y-2 hover:shadow-2xl">
          <img class="object-cover w-full h-56 md:h-64 xl:h-80" src=".\images\Inscription.png?auto=compress&amp" alt="" />
          <div class="absolute inset-0 px-6 py-4 transition-opacity duration-200 bg-black bg-opacity-75 opacity-0 hover:opacity-100">
            <p class="mb-4 text-lg font-bold text-gray-100">Sig up page</p>
            <p class="text-sm tracking-wide text-gray-300">
                For new users who want to access the service for the first time. It includes two password fields for confirmation to prevent typing errors. The passwords are then hashed before being stored in the database, and an access token with a 30-minute validity is generated.
            </p>
          </div>
        </div>
      </a>
      <a href="/" aria-label="View Item">
        <div class="relative overflow-hidden transition duration-200 transform rounded shadow-lg hover:-translate-y-2 hover:shadow-2xl">
          <img class="object-cover w-full h-56 md:h-64 xl:h-80" src="./images/EnvoyerMessage.png?auto=compress&amp" alt="" />
          <div class="absolute inset-0 px-6 py-4 transition-opacity duration-200 bg-black bg-opacity-75 opacity-0 hover:opacity-100">
            <p class="mb-4 text-lg font-bold text-gray-100">Send message to sidemen</p>
            <p class="text-sm tracking-wide text-gray-300">
                Displays a search for sidemen available for a concert date and allows sending notifications to all matching profiles.
            </p>
          </div>
        </div>
      </a>
      <a href="/" aria-label="View Item">
        <div class="relative overflow-hidden transition duration-200 transform rounded shadow-lg hover:-translate-y-2 hover:shadow-2xl">
          <img class="object-cover w-full h-56 md:h-64 xl:h-80" src="./images/Notification.png?auto=compress&amp" alt="" />
          <div class="absolute inset-0 px-6 py-4 transition-opacity duration-200 bg-black bg-opacity-75 opacity-0 hover:opacity-100">
            <p class="mb-4 text-lg font-bold text-gray-100">Notifications</p>
            <p class="text-sm tracking-wide text-gray-300">
                Musicians can view all announcements posted by music groups.
            </p>
          </div>
        </div>
      </a>
      <a href="/" aria-label="View Item">
        <div class="relative overflow-hidden transition duration-200 transform rounded shadow-lg hover:-translate-y-2 hover:shadow-2xl">
          <img class="object-cover w-full h-56 md:h-64 xl:h-80" src="./images/RechercheList.png?auto=compress&amp" alt="" />
          <div class="absolute inset-0 px-6 py-4 transition-opacity duration-200 bg-black bg-opacity-75 opacity-0 hover:opacity-100">
            <p class="mb-4 text-lg font-bold text-gray-100">Search list of sidemen</p>
            <p class="text-sm tracking-wide text-gray-300">
                Search for a list of sidemen that match the requirements and the ability to contact them individually.
            </p>
          </div>
        </div>
      </a>
    </div>
    
  </div>

      <!-- FAQ section -->
      

 

       <!-- About section -->
       <h2 id="About" class="max-w-lg mb-5 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none md:mb-6 group">
        <span class="inline-block mb-1 sm:mb-4">
          About<br class="hidden md:block" />
          
        </span>
        <div class="h-1 ml-auto duration-300 origin-left transform bg-deep-purple-accent-400 scale-x-30 group-hover:scale-x-100"></div>
      </h2>
  <div class="relative overflow-hidden transition duration-300 transform rounded shadow-lg lg:hover:-translate-y-2 hover:shadow-2xl">
          <img class="object-cover h-80 " src=".\images\marianne.png" alt="Person" />
          <div class="absolute inset-0 flex flex-col justify-center px-5 py-4 text-center transition-opacity duration-300 bg-black bg-opacity-75 opacity-0 hover:opacity-100">
            <p class="mb-1 text-lg font-bold text-gray-100">Marianne Arrué</p>
            <p class="mb-4 text-ms text-gray-100">Student Software Developer</p>
            <p class="mb-4 text-ms tracking-wide text-gray-400">
                Music has always held a significant place in my life, so why not combine work and passion to find practical solutions.
            </p>
            <p class="mb-4 text-ms tracking-wide text-gray-400">
                Switching between roles as a biotechnology engineer and a science communicator/mediator, my career evolves with my continuous learning. Being curious and passionate, I constantly enrich my skills to create connections and actively engage in projects I believe in.
            </p>
           </div>
        </div>

      <!-- Footer section -->

  <div class=" bg-orange px-4 pt-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8">
    <div class="grid gap-10 row-gap-6 mb-8 sm:grid-cols-2 lg:grid-cols-4">
      <div class="sm:col-span-2">
        <img src=".\images\SidemanBand_slogan.png" alt="Logo de votre entreprise" class="inline-flex items-center lg:mx-auto"  >
        <div class="mt-6 lg:max-w-sm">
          <p class="text-sm text-gray-800">
            For music bands: efficiently find one or more replacements for your concerts.
          </p>
          <p class="mt-4 text-sm text-gray-800">
            For musicians: inform nearby orchestras that you are available as substitutes for their concert dates.
          </p>
        </div>
      </div>
      <div class="space-y-2 text-sm">
        <p class="text-base font-bold tracking-wide text-gray-900">Contacts</p>
        
        <div class="flex">
          <p class="mr-1 text-gray-800">Email:</p>
          <a href="mailto:5608@holbertonstudents.com" aria-label="Our email" title="Our email" class="transition-colors duration-300 text-deep-purple-accent-400 hover:text-deep-purple-800">5608@holbertonstudents.com</a>
        </div>
        <div class="flex">
          <p class="mr-1 text-gray-800">Address:</p>
          <a href="https://www.google.com/maps" target="_blank" rel="noopener noreferrer" aria-label="Our address" title="Our address" class="transition-colors duration-300 text-deep-purple-accent-400 hover:text-deep-purple-800">
            Toulouse
          </a>
        </div>
      </div>
      <div>
        <span class="text-base font-bold tracking-wide text-gray-900">Social</span>
        <div class="flex items-center mt-1 space-x-3">
          <a href="https://github.com/MarianneHolbie" class="text-gray-800 transition-colors duration-300 hover:text-deep-purple-accent-400">
            <svg aria-hidden="true" class="octicon octicon-mark-github h-6" fill="currentColor"  height="24" version="1.1" viewBox="0 0 16 16" width="24">
                <path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path>
            </svg>
           
          </a>
          <a href="https://www.linkedin.com/in/mariannearrue/" class="text-gray-800 transition-colors duration-300 hover:text-deep-purple-accent-400">
            <svg aria-hidden="true" class="octicon octicon-mark-github h-6" viewBox="0 0 24 24" fill="currentColor" >
                <path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/>
            </svg>

          </a>
          
        </div>
        <p class="mt-4 text-sm text-gray-800">
          Follow me on Github or LinkedIn
        </p>
      </div>
    </div>
    <div class="flex flex-col-reverse justify-between pt-5 pb-10 border-t lg:flex-row">
      <p class="text-sm text-gray-600">
        © Copyright 2023 Marianne Arrué. All rights reserved.
      </p>
      <ul class="flex flex-col mb-3 space-y-2 lg:mb-0 sm:space-y-0 sm:space-x-5 sm:flex-row">
            <li>
          <a href="/" class="text-sm text-gray-600 transition-colors duration-300 hover:text-deep-purple-accent-400">Privacy Policy</a>
        </li>
        <li>
          <a href="/" class="text-sm text-gray-600 transition-colors duration-300 hover:text-deep-purple-accent-400">Terms &amp; Conditions</a>
        </li>
      </ul>
    </div>
  </div>