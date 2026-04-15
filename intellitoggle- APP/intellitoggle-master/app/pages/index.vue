<template>
  <!-- Hero Section -->
  <div
    class="min-h-screen bg-[url('~/assets/images/herobg-mobile.png')]
    md:bg-[url('~/assets/images/herobg.png')] bg-cover bg-center bg-no-repeat md:flex md:items-center md:justify-center text-white pt-20 lg:pt-[150px] px-4">
    <div class="w-full max-w-7xl">
      <div class="text-center mb-12 lg:mb-[141px]">
        <h1 class="text-3xl sm:text-4xl md:text-5xl lg:text-[64px] font-bold leading-tight">
          The First <span
            class="bg-[#F9A71E] px-2 py-1 rounded-[8px] text-[#0F1026] inline-block mt-1">Dart-Native</span> Feature
          Flag<br /> With
          DartCodeAI
        </h1>
        <p class="mt-4 text-lg sm:text-xl md:text-2xl lg:text-[32px] leading-relaxed">
          Feature flags built for Dart, Ship faster, roll back<br /> safely, and scale with
          AI-powered
          delivery<br /> <span class="text-[#F9A71E]">Starting at just $1/month</span>
        </p>

        <div class="mt-8 flex flex-col sm:flex-row justify-center gap-4">
          <button class="bg-[#F9A71E] text-[#0F1026] px-6 py-3 rounded-[8px] font-bold w-full sm:w-[260px]">
            Get Access
          </button>
          <button class="border border-[#F9A71E] text-[#F9A71E] px-6 py-3 rounded-[8px] font-bold w-full sm:w-[260px]">
            Join AI Early Access
          </button>
        </div>
      </div>

      <div class="flex justify-center">
        <img src="~/assets/images/productimage.png" alt="SAAS Product Image"
          class="w-full  h-auto lg:w-[1394px] lg:h-[842px]">
      </div>
    </div>
  </div>

  <!-- Brands Section -->
  <div class="py-12 lg:py-[120px] px-4 lg:px-0 flex justify-center items-center">
    <div class="w-full max-w-7xl">
      <h1 class="text-center text-[#1A1C3D] md:font-semibold text-xl lg:text-[24px] mb-8 lg:mb-[40px]">
        Trusted by various engineering teams
      </h1>

      <div class="flex flex-wrap justify-center gap-6 lg:gap-[100px] items-center">
        <div class="w-24 lg:w-auto">
          <img src="~/assets/images/googlecloud.png" alt="Google Cloud" class="w-full h-auto">
        </div>
        <div class="w-24 lg:w-auto">
          <img src="~/assets/images/aws.png" alt="AWS" class="w-full h-auto">
        </div>
        <div class="w-24 lg:w-auto">
          <img src="~/assets/images/azure.png" alt="Azure" class="w-full h-auto">
        </div>
        <div class="w-24 lg:w-auto">
          <img src="~/assets/images/dg.png" alt="Digital Ocean" class="w-full h-auto">
        </div>
        <div class="w-24 lg:w-auto">
          <img src="~/assets/images/ibm.png" alt="IBM" class="w-full h-auto">
        </div>
      </div>
    </div>
  </div>

  <!-- What is IntelliToggle -->
  <div class="py-12 lg:py-[120px] px-4 lg:px-[120px]">
    <h1 class="hidden md:block text-center text-[#0F1026] text-3xl lg:text-[40px] font-semibold mb-8 lg:mb-[48px]">
      What is IntelliToggle
    </h1>
    <div class="flex flex-col lg:flex-row items-center justify-between gap-8 lg:gap-0">
      <div class="max-w-full lg:max-w-[623px]">
        <h2 class="text-2xl lg:text-[32px] font-semibold text-[#0E121B] mb-4 lg:mb-[16px]">
          Your AI Dart App's Control Panel For Feature Releases
        </h2>
        <p class="text-[#5F5F60] text-sm mb-4 lg:mb-[8px]">
          IntelliToggle is a "Dart-Powered" feature flag that lets you turn features on/off instantly in your
          application without redeploying code. It allows you control roll-outs, run experiments, and fix bugs faster.
        </p>
        <h3 class="text-[#0E121B] font-semibold text-xl lg:text-[24px] mb-2">Benefits</h3>
        <div>
          <ul class="space-y-1">
            <li class="text-[#5F5F60] text-sm">• Toggle new features without app updates</li>
            <li class="text-[#5F5F60] text-sm">• Roll out to specific users or regions</li>
            <li class="text-[#5F5F60] text-sm">• Instantly rollback when needed</li>
          </ul>
        </div>
      </div>
      <div class="w-full lg:w-auto">
        <img src="~/assets/images/product.png" alt="SAAS Product Image"
          class="w-full max-w-2xl h-auto lg:w-[830px] lg:h-[618px]">
      </div>
    </div>
  </div>

  <!-- OpenFeature Section -->
  <section class="md:bg-[#EDECF6]">
    <div
      class="py-12 lg:py-[120px] px-4 lg:px-[120px] flex flex-col lg:flex-row items-center justify-between gap-8 lg:gap-0">
      <div class="w-full lg:w-auto order-1 lg:order-1">
        <img src="~/assets/images/opf.png" alt="SAAS Product Image"
          class="w-full max-w-2xl h-auto lg:w-[830px] lg:h-[618px]">
      </div>
      <div class="max-w-full lg:max-w-[623px] order-1 lg:order-2">
        <h2 class="text-2xl lg:text-[32px] font-semibold text-[#0E121B] mb-4 lg:mb-[16px]">
          Seamless Feature Management with OpenFeature
        </h2>
        <p class="text-[#5F5F60] text-sm mb-4 lg:mb-[8px]">
          Aortem now integrates with OpenFeature to provide developers with a powerful, standardized approach to feature
          flagging and dynamic configuration. Ship features faster, test safely, and optimize user experiences
          effortlessly.
        </p>
        <div>
          <button
            class="hidden md:block flex gap-2 items-center bg-[#F9A71E] px-6 py-3 lg:px-[24px] lg:py-[12px] rounded-[8px] text-[#0F1026] font-semibold text-sm lg:text-base">
            <p>Learn More</p>
            <img src="~/assets/images/right-arrow.svg" alt="arrow right" class="w-4 h-4">
          </button>
          <button
            class="flex justify-center gap-2 items-center bg-gradient-to-b from-[#42389E] to-[#0F1026] w-full px-6 py-3 lg:px-[24px] lg:py-[12px] rounded-[8px] text-[#ffffff] font-semibold text-sm lg:text-base">
            <p>Learn More</p>
            <img src="~/assets/images/ra_mobile.svg" alt="arrow right" class="w-4 h-4">
          </button>
        </div>
      </div>
    </div>
  </section>

  <!-- Control Section -->
  <section class="py-12 lg:py-[120px] px-4 lg:px-[120px]">
    <h1 class="text-center text-[#0F1026] text-3xl lg:text-[40px] font-semibold mb-8 lg:mb-[48px]">
      Control & Power focused
    </h1>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 lg:gap-[95px]">
      <div class="flex flex-col ">
        <img src="~/assets/images/c1.png" alt="Feature 1" class="w-full max-w-md h-auto lg:w-[497px] lg:h-[363px]">
        <div class="mt-4 lg:mt-[16px] mb-4 lg:mb-[32px]">
          <h1 class="text-[#1A1C3D] text-xl lg:text-[24px] font-semibold">Connect</h1>
          <p class="text-[#5F5F60] text-base lg:text-[18px]">Install SDK in your Dart project in 2 mins.</p>
        </div>
        <button
          class="border border-[#F9A71E] text-[#F9A71E] px-6 py-3 rounded-[8px] font-bold w-full max-w-xs lg:w-[260px]">
          View Documentation
        </button>
      </div>
      <div class="flex flex-col">
        <img src="~/assets/images/c2.png" alt="Feature 1" class="w-full max-w-md h-auto lg:w-[497px] lg:h-[363px]">
        <div class="mt-4 lg:mt-[16px] mb-4 lg:mb-[32px]">
          <h1 class="text-[#1A1C3D] text-xl lg:text-[24px] font-semibold">Create Flags</h1>
          <p class="text-[#5F5F60] text-base lg:text-[18px]">Define features in IntelliToggle dashboard.</p>
        </div>
        <button
          class="border border-[#F9A71E] text-[#F9A71E] px-6 py-3 rounded-[8px] font-bold w-full max-w-xs lg:w-[260px]">
          View Documentation
        </button>
      </div>
      <div class="flex flex-col md:col-span-2 lg:col-span-1">
        <img src="~/assets/images/c3.png" alt="Feature 1" class="w-full max-w-md h-auto lg:w-[497px] lg:h-[363px]">
        <div class="mt-4 lg:mt-[16px] mb-4 lg:mb-[32px]">
          <h1 class="text-[#1A1C3D] text-xl lg:text-[24px] font-semibold">Ship & Control</h1>
          <p class="text-[#5F5F60] text-base lg:text-[18px]">Flip switches anytime, see instant results.</p>
        </div>
        <button
          class="border border-[#F9A71E] text-[#F9A71E] px-6 py-3 rounded-[8px] font-bold w-full max-w-xs lg:w-[260px]">
          View Documentation
        </button>
      </div>
    </div>
  </section>

  <!-- Feature Comparison -->
  <section class="py-12 lg:py-[120px] px-4 lg:px-[120px]">
    <h1 class="text-center text-[#0F1026] text-3xl lg:text-[40px] font-semibold mb-8 lg:mb-[48px]">
      Dart-Powered Feature Flag
    </h1>

    <div class="mb-8 lg:mb-0">
      <h2 class="text-[#1A1C3D] md:text-center font-semibold text-xl lg:text-[32px] mb-2">
        Not Another Generic Feature Flag Tool
      </h2>
      <p class="text-[#5F5F60] md:text-center text-sm lg:text-base">
        Most tools are built for every language, which means extra layers and slower toggles.<br /> IntelliToggle is
        built in
        Dart, for Dart — so it's faster, safer, and built for your stack.
      </p>
    </div>

    <div class="mt-8 lg:mt-[32px] flex justify-center">
      <div class="w-full max-w-7xl rounded-[16px] overflow-hidden">
        <div
          class="grid grid-cols-3 items-center px-4 lg:px-[32px] py-3 lg:py-[12px] bg-gradient-to-t from-[#1A1C3D] to-[#2B2E6F] text-white text-sm lg:text-[18px] font-semibold">
          <div>Features</div>
          <div class="text-center">IntelliToggle</div>
          <div class="text-center">Other Feature Flag</div>
        </div>

        <div class="bg-[#F5F4FB] text-[#5F5F60]">
          <div class="grid grid-cols-3 items-center px-5 lg:px-[32px] py-3 lg:py-[10px] text-sm lg:text-base">
            <div class="font-medium text-[#5F5F60]">Dart-native SDK & server</div>
            <div class="flex justify-center">
              <span class="text-[#1A1C3D]">
                <img src="~/assets/images/tick.svg" alt="tick" class="w-4 h-4 lg:w-6 lg:h-6">
              </span>
            </div>
            <div class="flex justify-center">
              <span class="text-[#1A1C3D]">
                <img src="~/assets/images/cross.svg" alt="cross" class="w-4 h-4 lg:w-6 lg:h-6">
              </span>
            </div>
          </div>

          <div class="grid grid-cols-3 items-center px-5 lg:px-[32px] py-3 lg:py-[10px] text-sm lg:text-base">
            <div class="font-medium text-[#5F5F60]">End-to-end type safety</div>
            <div class="flex justify-center">
              <span class="text-[#1A1C3D]">
                <img src="~/assets/images/tick.svg" alt="tick" class="w-4 h-4 lg:w-6 lg:h-6">
              </span>
            </div>
            <div class="flex justify-center">
              <span class="text-[#1A1C3D]">
                <img src="~/assets/images/cross.svg" alt="cross" class="w-4 h-4 lg:w-6 lg:h-6">
              </span>
            </div>
          </div>

          <div class="grid grid-cols-3 items-center px-5 lg:px-[32px] py-3 lg:py-[10px] text-sm lg:text-base">
            <div class="font-medium text-[#5F5F60]">AI-assisted roll-outs & cleanup</div>
            <div class="flex justify-center">
              <span class="text-[#1A1C3D]">
                <img src="~/assets/images/tick.svg" alt="tick" class="w-4 h-4 lg:w-6 lg:h-6">
              </span>
            </div>
            <div class="flex justify-center">
              <span class="text-[#1A1C3D]">
                <img src="~/assets/images/cross.svg" alt="cross" class="w-4 h-4 lg:w-6 lg:h-6">
              </span>
            </div>
          </div>

          <div class="grid grid-cols-3 items-center px-5 lg:px-[32px] py-3 lg:py-[10px] text-sm lg:text-base">
            <div class="font-medium text-[#5F5F60]">A/B testing built-in</div>
            <div class="flex justify-center">
              <span class="text-[#1A1C3D]">
                <img src="~/assets/images/tick.svg" alt="tick" class="w-4 h-4 lg:w-6 lg:h-6">
              </span>
            </div>
            <div class="flex justify-center">
              <span class="text-[#1A1C3D]">
                <img src="~/assets/images/cross.svg" alt="cross" class="w-4 h-4 lg:w-6 lg:h-6">
              </span>
            </div>
          </div>

          <div class="grid grid-cols-3 items-center px-4 lg:px-[32px] py-3 lg:py-[10px] text-sm lg:text-base">
            <div class="font-medium text-[#5F5F60]">Dart-Powered SDKs</div>
            <div class="flex justify-center">
              <span class="text-[#1A1C3D]">
                <img src="~/assets/images/tick.svg" alt="tick" class="w-4 h-4 lg:w-6 lg:h-6">
              </span>
            </div>
            <div class="flex justify-center">
              <span class="text-[#1A1C3D]">
                <img src="~/assets/images/cross.svg" alt="cross" class="w-4 h-4 lg:w-6 lg:h-6">
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- DartCodeAI Section -->
  <section
    class="w-full py-12 lg:py-[120px] px-4 lg:px-[120px] text-white bg-[url('~/assets/images/ai.png')] bg-cover bg-center bg-no-repeat overflow-hidden">
    <div class="relative z-10 max-w-7xl mx-auto">
      <div class="flex justify-center mb-6 lg:mb-[24px]">
        <span
          class="bg-[#F9A71E] text-[#0F1026] text-sm lg:text-[14px] font-semibold px-4 lg:px-[16px] py-1 lg:py-[6px] rounded-full">
          Coming Soon
        </span>
      </div>

      <h1 class="text-center text-2xl lg:text-[40px] font-semibold mb-8 lg:mb-[72px]">
        DartCodeAI That Actually Changes Flagging
      </h1>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6 lg:gap-[40px] mb-8 lg:mb-[64px]">
        <div
          class="border border-white/20 backdrop-blur-sm p-4 lg:p-[32px] rounded-lg text-center shadow-[0_0px_6px_-1.76px_rgba(255,255,225,0.8)] flex flex-col items-center justify-center">
          <div class="mb-4 lg:mb-[16px]">
            <div class="w-10 h-10 lg:w-[40px] lg:h-[40px] rounded-[8px] bg-white flex items-center justify-center">
              <img src="~/assets/images/flag-icon.png" class="w-5 h-5 lg:w-[20px] lg:h-[20px]" />
            </div>
          </div>

          <h3 class="text-lg lg:text-[20px] font-semibold mb-2 lg:mb-[8px] text-white">
            AutoFlag AI (LLM-Assisted Flag Creation)
          </h3>

          <p class="text-sm lg:text-[16px] text-white/80 leading-relaxed">
            Create new flags just by typing what you need. The AI names it, sets rules, and configures targeting for
            you.
          </p>
        </div>

        <div
          class="border border-white/20 backdrop-blur-sm p-4 lg:p-[32px] rounded-lg text-center shadow-[0_0px_6px_-1.76px_rgba(255,255,225,0.8)] flex flex-col items-center justify-center">
          <div class="mb-4 lg:mb-[16px]">
            <div class="w-10 h-10 lg:w-[40px] lg:h-[40px] rounded-[8px] bg-white flex items-center justify-center">
              <img src="~/assets/images/robot-icon.png" class="w-5 h-5 lg:w-[20px] lg:h-[20px]" />
            </div>
          </div>

          <h3 class="text-lg lg:text-[20px] font-semibold mb-2 lg:mb-[8px] text-white">
            SmartRamp AI (AI-Driven Rollout Optimization)
          </h3>

          <p class="text-sm lg:text-[16px] text-white/80 leading-relaxed">
            Rollouts that adjust themselves. AI expands, pauses, or rolls back based on real-time metrics.
          </p>
        </div>

        <div
          class="border border-white/20 backdrop-blur-sm p-4 lg:p-[32px] rounded-lg text-center shadow-[0_0px_6px_-1.76px_rgba(255,255,225,0.8)] flex flex-col items-center justify-center">
          <div class="mb-4 lg:mb-[16px]">
            <div class="w-10 h-10 lg:w-[40px] lg:h-[40px] rounded-[8px] bg-white flex items-center justify-center">
              <img src="~/assets/images/search-icon.png" class="w-5 h-5 lg:w-[20px] lg:h-[20px]" />
            </div>
          </div>

          <h3 class="text-lg lg:text-[20px] font-semibold mb-2 lg:mb-[8px] text-white">
            ExplainFlags AI (LLM Root-Cause + Insights)
          </h3>

          <p class="text-sm lg:text-[16px] text-white/80 leading-relaxed">
            Understand issues instantly with AI-generated, plain-language insights tied to your flags.
          </p>
        </div>

        <div
          class="border border-white/20 backdrop-blur-sm p-4 lg:p-[32px] rounded-lg text-center shadow-[0_0px_6px_-1.76px_rgba(255,255,225,0.8)] flex flex-col items-center justify-center">
          <div class="mb-4 lg:mb-[16px]">
            <div class="w-10 h-10 lg:w-[40px] lg:h-[40px] rounded-[8px] bg-white flex items-center justify-center">
              <img src="~/assets/images/chart-icon.png" class="w-5 h-5 lg:w-[20px] lg:h-[20px]" />
            </div>
          </div>

          <h3 class="text-lg lg:text-[20px] font-semibold mb-2 lg:mb-[8px] text-white">
            AutoSegment AI (Behavioral Segmentation)
          </h3>

          <p class="text-sm lg:text-[16px] text-white/80 leading-relaxed">
            Target the right users automatically. AI builds segments from live behavior—no manual rules.
          </p>
        </div>
      </div>

      <!-- Enterprise Only -->
      <p class="text-center text-[#F9A71E] text-xl lg:text-[32px] font-semibold mb-8 lg:mb-[48px]">
        Enterprise Only
      </p>

      <!-- CTA -->
      <div
        class="flex flex-col lg:flex-row items-center justify-between border rounded-[16px] p-4 lg:px-[32px] lg:py-[24px] border-white/20 backdrop-blur-sm shadow-[0_0px_6px_-1.76px_rgba(255,255,225,0.8)] gap-4 lg:gap-0">
        <p class="text-base lg:text-[18px] font-semibold text-center lg:text-left mb-4 lg:mb-0">
          <span class="text-[#F9A71E]">Be The First</span> To Try Out Our New AI Features.
        </p>

        <div
          class="flex flex-col sm:flex-row items-center gap-2 border border-white/30 rounded-[8px] p-1 w-full lg:w-auto">
          <input type="email" placeholder="Enter email address"
            class="bg-transparent px-4 py-2 text-white placeholder:text-white/50 w-full sm:w-[280px] focus:outline-none" />
          <button class="bg-[#F9A71E] text-[#0F1026] font-semibold px-6 py-2 rounded-[6px] w-full sm:w-auto">
            Join AI Early Access
          </button>
        </div>
      </div>
    </div>
  </section>

  <!-- Plans Section -->
  <section class="py-12 lg:py-[120px] px-4 lg:px-[120px] bg-[#EDECF6]">
    <h1 class="text-center text-[#0F1026] text-3xl lg:text-[40px] font-semibold mb-8 lg:mb-[48px]">
      Plans Built For Every Stage Of Growth
    </h1>

    <!-- MOBILE PRICING CARD -->
    <section class="lg:hidden px-4 py-12 bg-[#EDECF6] flex justify-center">
      <div
        class="w-full max-w-sm rounded-[28px] bg-gradient-to-b from-[#42389E] to-[#0F1026] text-white p-6 relative shadow-xl">

        <!-- Popular Badge -->
        <span class="absolute top-6 left-6 bg-[#F9A71E] text-[#0F1026] font-semibold text-sm px-4 py-1 rounded-full">
          Popular
        </span>

        <!-- Billed annually -->
        <span class="absolute top-6 right-6 bg-[#EDECF6] text-[#1A1C3D] text-sm px-4 py-1 rounded-full rotate-12">
          Billed annually
        </span>

        <!-- Title -->
        <h3 class="mt-16 text-2xl font-semibold mb-6">
          Enhance Plan
        </h3>

        <!-- Price -->
        <div class="flex items-end gap-2 mb-6">
          <span class="text-6xl font-bold">$149</span>
          <span class="text-xl mb-2">/month</span>
        </div>

        <!-- Divider -->
        <div class="h-px bg-white/20 mb-6"></div>

        <!-- Features -->
        <ul class="space-y-4 text-sm leading-relaxed">
          <li class="flex gap-3">
            <span>✓</span>
            <span>Multi-environment support (Dev / Staging / Prod)</span>
          </li>
          <li class="flex gap-3">
            <span>✓</span>
            <span>Unlimited feature flags and projects</span>
          </li>
          <li class="flex gap-3">
            <span>✓</span>
            <span>Advanced targeting rules with custom attributes</span>
          </li>
          <li class="flex gap-3">
            <span>✓</span>
            <span>Environment-specific flags</span>
          </li>
          <li class="flex gap-3">
            <span>✓</span>
            <span>Real-time streaming updates (WebSocket / gRPC)</span>
          </li>
          <li class="flex gap-3">
            <span>✓</span>
            <span>Analytics hooks (flag usage tracking)</span>
          </li>
          <li class="flex gap-3">
            <span>✓</span>
            <span>Built-in A/B testing / experimentation dashboard</span>
          </li>
          <li class="flex gap-3">
            <span>✓</span>
            <span>Audit logs (90-day retention + export in CSV/JSON)</span>
          </li>
          <li class="flex gap-3">
            <span>✓</span>
            <span>API access with multiple keys & custom roles</span>
          </li>
        </ul>

        <!-- CTA -->
        <button class="mt-8 w-full border border-white rounded-xl py-4 text-lg font-semibold">
          Subscribe
        </button>
      </div>
    </section>


    <div class="flex justify-center">
      
      <div class="flex flex-col items-center w-full max-w-7xl">
        <div
          class="hidden md:block bg-gradient-to-b from-[#42389E] to-[#0F1026] p-6 lg:p-[24px] rounded-[12px] w-full max-w-md lg:w-[370px] mb-4 lg:mb-[16px]">
          <h3 class="text-[#FEFEFF] font-semibold text-center text-lg lg:text-[20px] mb-4 lg:mb-[21px]">
            Prices starts at
          </h3>

          <div class="text-center mb-4 lg:mb-[24px]">
            <span class="text-[#FEFEFF] text-4xl lg:text-[48px] font-bold mr-2 lg:mr-[18px]">$10</span>
            <span class="text-[#FEFEFF] text-xl lg:text-[24px]">/month</span>
          </div>
        </div>

        <button
          class="hidden md:block bg-[#F9A71E] text-[#0F1026] px-6 py-3 lg:px-[20px] lg:py-[10px] rounded-[8px] font-bold w-full max-w-md lg:w-[370px]">
          View Subscription Details
        </button>

        <div
          class="bg-white border-[0.5px] border-[#0F1026] py-8 lg:py-[64px] px-4 lg:px-[32px] w-full mt-6 lg:mt-[32px] rounded-lg flex flex-col lg:flex-row items-center justify-between gap-6 lg:gap-0">
          <div class="text-center lg:text-left">
            <h1 class="text-[#1A1C3D] text-xl lg:text-[32px] font-semibold">
              Start Your 7-Day Free Sandbox Plan
            </h1>
            <p class="text-[#5F5F60]">
              Join over 1,000+ startups already growing with Untitled.
            </p>
          </div>
          <div class="flex flex-col sm:flex-row gap-4 w-full sm:w-auto">
            <button
              class="bg-[#F9A71E] text-[#0F1026] px-6 py-3 lg:px-[24px] lg:py-[12px] rounded-[8px] font-bold w-full sm:w-[184px]">
              Get Started
            </button>
            <button
              class="border border-[#F9A71E] text-[#F9A71E] px-6 py-3 lg:px-[24px] lg:py-[12px] rounded-[8px] font-bold w-full sm:w-[184px]">
              Learn More
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Why Teams Use -->
  <section class="hidden md:block py-12 lg:py-[120px] px-4 lg:px-[120px]">
    <h1 class="text-center text-[#0F1026] text-3xl lg:text-[40px] font-semibold mb-8 lg:mb-[48px]">
      Why Teams Use IntelliToggle
    </h1>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 lg:gap-0 mb-8 lg:mb-[32px]">
      <div class="flex flex-col items-center text-center">
        <div
          class="bg-[#EDECF6] border-[1px] border-[#0F1026] rounded-[8px] flex justify-center items-center w-24 h-24 lg:w-[129px] lg:h-[118px] mb-4 lg:mb-[48px]">
          <img src="~/assets/images/control.png" alt="" class="w-8 h-8 lg:w-[37.5px] lg:h-[37.5px]">
        </div>
        <h2 class="text-[#1A1C3D] text-xl lg:text-[24px] font-semibold mb-2">Safer, faster rollouts</h2>
        <p class="text-[#5F5F60]">Control feature releases in minutes, not weeks without risking production stability.
        </p>
      </div>
      <div class="flex flex-col items-center text-center">
        <div
          class="bg-[#EDECF6] border-[1px] border-[#0F1026] rounded-[8px] flex justify-center items-center w-24 h-24 lg:w-[129px] lg:h-[118px] mb-4 lg:mb-[48px]">
          <img src="~/assets/images/code.png" alt="" class="w-8 h-8 lg:w-[37.5px] lg:h-[37.5px]">
        </div>
        <h2 class="text-[#1A1C3D] text-xl lg:text-[24px] font-semibold mb-2">Dart-native performance</h2>
        <p class="text-[#5F5F60]">Built for Dart apps with native performance and type safety.</p>
      </div>
      <div class="flex flex-col items-center text-center">
        <div
          class="bg-[#EDECF6] border-[1px] border-[#0F1026] rounded-[8px] flex justify-center items-center w-24 h-24 lg:w-[129px] lg:h-[118px] mb-4 lg:mb-[48px]">
          <img src="~/assets/images/operator.png" alt="" class="w-8 h-8 lg:w-[37.5px] lg:h-[37.5px]">
        </div>
        <h2 class="text-[#1A1C3D] text-xl lg:text-[24px] font-semibold mb-2">AI-powered insights</h2>
        <p class="text-[#5F5F60]">Get intelligent suggestions for feature rollouts and user segmentation.</p>
      </div>
    </div>

    <div
      class="bg-[#EDECF6] py-4 px-4 lg:py-[16px] lg:px-[32px] border-[0.2px] border-[#0F1026] rounded-[12px] flex flex-col lg:flex-row justify-between items-center gap-4 lg:gap-0">
      <p class="text-lg lg:text-[24px] font-semibold text-[#5F5F60] text-center lg:text-left">
        <span class="text-[#0E121B]">Read a 2-min case note:</span>
        How a sample Flutter app shipped faster with IntelliToggle
      </p>
      <button
        class="bg-[#F9A71E] text-[#0F1026] px-6 py-3 lg:px-[24px] lg:py-[12px] rounded-[8px] font-bold w-full lg:w-[184px]">
        Read Now
      </button>
    </div>
  </section>

  <!-- Final CTA Section -->
  <section class="py-12 lg:py-[120px] px-4 lg:px-[120px] flex justify-center items-center">
    <div
      class="bg-[#42389E] rounded-[12px] md:bg-[url('~/assets/images/bgpattern.png')] bg-cover bg-center bg-no-repeat px-4 lg:px-[77px] text-white h-auto lg:h-[375px] w-full max-w-7xl text-center py-8 lg:py-[68px]">
      <h2 class="text-xl lg:text-[32px] font-semibold mb-4 lg:mb-[12px]">
        Launch Features Confidently With AI Driven Feature Flags
      </h2>
      <p class="text-[#FAFAFA] text-base lg:text-[18px]">Start for free, scale as your team grows</p>

      <div class="mt-8 flex flex-col sm:flex-row justify-center gap-4">
        <button class="bg-[#F9A71E] text-[#0F1026] px-6 py-3 rounded-[8px] font-bold w-full sm:w-[260px]">
          Start for $1/mo
        </button>
        <button class="border border-[#F9A71E] text-[#F9A71E] px-6 py-3 rounded-[8px] font-bold w-full sm:w-[260px]">
          Join AI Early Access
        </button>
      </div>
    </div>
  </section>
</template>