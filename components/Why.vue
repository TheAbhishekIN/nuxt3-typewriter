<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div class="relative bg-white pt-16 pb-32 overflow-hidden">
    <div class="relative">
      <div class="lg:mx-auto lg:max-w-7xl lg:px-8 lg:grid lg:grid-cols-2 lg:grid-flow-col-dense lg:gap-24">
        <div class="px-4 max-w-xl mx-auto sm:px-6 lg:py-16 lg:max-w-none lg:mx-0 lg:px-0">
          <div>
            <div>
              <h2 class="text-base font-semibold text-indigo-600 tracking-wide uppercase">"Garbage In, Garbage Out"</h2>
            </div>
            <div class="mt-6">
              <h2 class="text-3xl font-extrabold tracking-tight text-gray-900">
                The Key to a Successful Web App
              </h2>
              <p class="mt-4 text-lg text-gray-500">
                Our team excels in bridging the gap between your business processes and the technical aspects of app development so everyone is in complete alignment. We spend 3-6 weeks deep diving into your organization and developing a rationalized, strategic build plan with detailed documentation so you can be sure we fully understand the nuances of your business and are confident that our build plan (if executed properly), will exceed your expectations. 
              </p>
              <!--<div class="mt-6">
                <a href="#" class="inline-flex px-4 py-2 border border-transparent text-base font-medium rounded-md shadow-sm text-white bg-indigo-600 hover:bg-indigo-700">
                  Get started
                </a>
              </div>-->
            </div>
          </div>
          <div class="mt-8 border-t border-gray-200 pt-6">
            <blockquote>
              <div>
                <p class="text-base text-gray-500">
                  &ldquo;These guys are focused on the actual and technical requirements and will ask the questions until they understand the project completely and will explain in layman’s terms.&rdquo;
                </p>
              </div>
              <footer class="mt-3">
                <div class="flex items-center space-x-3">
                  <div class="flex-shrink-0">
                    <img class="h-6 w-6 rounded-full" src="https://images.unsplash.com/photo-1509783236416-c9ad59bae472?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="" />
                  </div>
                  <div class="text-base font-medium text-gray-700">
                    Calista Green, Harcourts Auctions
                  </div>
                </div>
              </footer>
            </blockquote>
          </div>
        </div>
        <div class="mt-12 sm:mt-16 lg:mt-0">
          <div class="pl-4 -mr-48 sm:pl-6 md:-mr-16 lg:px-0 lg:m-0 lg:relative lg:h-full">
            <img class="w-full rounded-xl shadow-xl ring-1 ring-black ring-opacity-5 lg:absolute lg:left-0 lg:h-full lg:w-auto lg:max-w-none" src="https://tailwindui.com/img/component-images/inbox-app-screenshot-1.jpg" alt="Inbox user interface" />
          </div>
        </div>
      </div>
    </div>
    <div class="mt-24">
      <div class="lg:mx-auto lg:max-w-7xl lg:px-8 lg:grid lg:grid-cols-2 lg:grid-flow-col-dense lg:gap-24">
        <div class="px-4 max-w-xl mx-auto sm:px-6 lg:py-32 lg:max-w-none lg:mx-0 lg:px-0 lg:col-start-2">
          <div>
            <h2 class="text-base font-semibold text-indigo-600 tracking-wide uppercase">Tech Stack</h2>
            <div class="mt-6">
              <h2 class="text-3xl font-extrabold tracking-tight text-gray-900">
                Tools of the Trade
              </h2>
              <p class="mt-4 text-lg text-gray-500">
                We are full-stack developers that use proven tools to ensure your project is scalable and highly serviceable for a long product life-cycle. In most cases, our tools will include Laravel (Backend), Vue (Frontend), Tailwind (CSS), and Amazon Web Services (Deployment). 
              </p>
              <div class="mt-6">
                <a href="#" class="inline-flex px-4 py-2 border border-transparent text-base font-medium rounded-md shadow-sm text-white bg-indigo-600 hover:bg-indigo-700">
                  Case Studies
                </a>
              </div>
                        <div class="mt-8 border-t border-gray-200 pt-6">
            <blockquote>
              <div>
                <p class="text-base text-gray-500">
                  &ldquo;Our previous student database would often fail durning enrollment. The new system has been rock solid and can handle any amount of traffic we throw at it without workarounds.&rdquo;
                </p>
              </div>
              <footer class="mt-3">
                <div class="flex items-center space-x-3">
                  <div class="flex-shrink-0">
                    <img class="h-6 w-6 rounded-full" src="https://images.unsplash.com/photo-1580489944761-15a19d654956?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=922&q=80" alt="" />
                  </div>
                  <div class="text-base font-medium text-gray-700">
                    Kerri Fung, Irvine Public School District
                  </div>
                </div>
              </footer>
            </blockquote>
          </div>
            </div>
          </div>
        </div>
        <div class="mt-12 sm:mt-16 lg:mt-0 lg:col-start-1">
          <div class="pr-4 -ml-48 sm:pr-6 md:-ml-16 lg:px-0 lg:m-0 lg:relative lg:h-full">
            <img class="w-full rounded-xl shadow-xl ring-1 ring-black ring-opacity-5 lg:absolute lg:right-0 lg:h-full lg:w-auto lg:max-w-none" src="https://tailwindui.com/img/component-images/inbox-app-screenshot-2.jpg" alt="Customer profile user interface" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { InboxIcon, SparklesIcon } from '@heroicons/vue/outline'

export default {
  components: {
    InboxIcon,
    SparklesIcon,
  },
}
</script>