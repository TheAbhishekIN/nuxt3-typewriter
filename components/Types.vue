<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div id="application-types" class="bg-gradient-to-r from-purple-800 to-indigo-700">
    <div class="max-w-4xl mx-auto px-4 py-16 sm:px-6 sm:pt-20 sm:pb-24 lg:max-w-7xl lg:pt-24 lg:px-8">
      <h2 class="text-3xl font-extrabold text-white tracking-tight">
        Types of Applications
      </h2>
      <p class="mt-4 max-w-3xl text-lg text-indigo-200">
        In the past decade, we have worked on hundreds of web applications in dozens of industries of all sizes (startups to global enterprises). Perhaps your application is a mixture of a few types or something completely new and unique. Either way, we have you covered.
      </p>
      <div class="mt-12 grid grid-cols-1 gap-x-6 gap-y-12 sm:grid-cols-2 lg:mt-16 lg:grid-cols-4 lg:gap-x-8 lg:gap-y-16">
        <div v-for="feature in features" :key="feature.name">
          <div>
            <span class="flex items-center justify-center h-12 w-12 rounded-md bg-white bg-opacity-10">
              <component :is="feature.icon" class="h-6 w-6 text-white" aria-hidden="true" />
            </span>
          </div>
          <div class="mt-6">
            <h3 class="text-lg font-medium text-white">{{ feature.name }}</h3>
            <p class="mt-2 text-base text-indigo-200">
              {{ feature.description }}
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import {
  DatabaseIcon,
  LinkIcon,
  LightningBoltIcon,
  CloudIcon,
  CurrencyDollarIcon,
  ChartBarIcon,
  CalculatorIcon,
  CalendarIcon,
} from '@heroicons/vue/outline'


const features = [
  {
    name: 'Database',
    description: 'Collect and extract meaningful data. Make better-informed decisions with helpful dashboards and trigger defined automations.',
    icon: DatabaseIcon,
  },
  {
    name: 'Blockchain',
    description: 'Create a Web3 application that leverages the power of smart contracts on one the most popular blockchain networks.',
    icon: LinkIcon,
  },
  {
    name: 'Workflow Automation',
    description: 'Are your current processes cumbersome and time-consuming? We can help automate and reduce waste.',
    icon: LightningBoltIcon,
  },
  {
    name: 'SaaS',
    description: 'Develop a software application as a service that can tie into almost any 3rd party platform with an accessible API. ',
    icon: CloudIcon,
  },
  {
    name: 'Customer Relationship',
    description: 'Pre-built CRMs often fall somewhere between too much or too little. We’ll only add the features you’ll use and make it dead simple.',
    icon: CurrencyDollarIcon,
  },
  {
    name: 'Project Management',
    description: 'Project management systems can often be overly complex. We can simplify and build it around your unique processes. ',
    icon: ChartBarIcon,
  },
  {
    name: 'Calculators & Estimation',
    description: 'We can help you create game-changing systems to make complex calculations incredibly simple and lightning fast. ',
    icon: CalculatorIcon,
  },
  {
    name: 'Scheduling & Orders',
    description: 'Need the ability to add calendar, scheduling, or electronic transactions functions to your systems? No problem. ',
    icon: CalendarIcon,
  },
]

export default {
  setup() {
    return {
      features,
    }
  },
}
</script>