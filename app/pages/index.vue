<template>
  <main>
    <section class="bg-gradient-to-b from-[#4338A6] to-[#151741] px-4 pb-16 pt-20 text-white md:px-8 md:pb-24 md:pt-24">
      <div class="mx-auto w-full max-w-[1240px]">
        <h1 class="max-w-[680px] text-[44px] font-semibold leading-[1.05] md:text-[72px]">IntelliToggle Website</h1>
      </div>
    </section>

    <section class="px-4 py-16 md:px-8">
      <div class="mx-auto w-full max-w-[1240px] rounded-[8px] border border-[#C8CAD8] bg-white p-6 md:p-8">
        <div class="grid grid-cols-1 gap-5 lg:grid-cols-3">
          <article class="rounded-[8px] border border-[#D8DAE5] bg-white p-5">
            <div class="mb-2 flex items-center justify-between">
              <h3 class="text-[14px] font-semibold text-[#23265A]">Standard Plan</h3>
              <span class="rounded-full bg-[#ECECF6] px-2 py-0.5 text-[9px] font-semibold text-[#5E6075]">billed annually</span>
            </div>
            <p class="mb-4 text-[40px] font-bold leading-none text-[#23265A]">$10 <span class="text-[16px] font-medium">/month</span></p>
            <ul class="space-y-2 text-[11px] text-[#4D4F64]">
              <li>✓ Core Feature Flags API</li>
              <li>✓ Targeting Rules Engine</li>
              <li>✓ Percentage Rollouts</li>
              <li>✓ Flutter Client SDK</li>
              <li>✓ Kill Switch / Instant Rollback</li>
              <li>✓ Dart Server SDK</li>
              <li>✕ Multi-environment support</li>
              <li>✕ Unlimited Flags & Projects</li>
            </ul>
            <button class="mt-6 w-full rounded-[6px] border border-[#BFC2D9] py-2 text-[11px] font-semibold text-[#24295C]">Subscribe</button>
          </article>

          <article class="relative rounded-[8px] bg-gradient-to-b from-[#4338A6] to-[#111330] p-5 text-white">
            <span class="absolute left-5 top-3 rounded-full bg-[#F9A71E] px-2.5 py-1 text-[9px] font-semibold text-[#0F1130]">Popular</span>
            <div class="mb-3 mt-5 flex items-center justify-between">
              <h3 class="text-[14px] font-semibold">Enhance Plan</h3>
              <span class="rounded-full bg-white/20 px-2 py-0.5 text-[9px]">billed annually</span>
            </div>
            <p class="mb-4 text-[40px] font-bold leading-none">$149 <span class="text-[16px] font-medium text-white/80">/month</span></p>
            <ul class="space-y-2 text-[11px] text-white/90">
              <li>✓ Multi-environment support (Dev/Staging/Prod)</li>
              <li>✓ Unlimited feature flags and projects</li>
              <li>✓ Advanced targeting rules</li>
              <li>✓ Environment-specific flags</li>
              <li>✓ Real-time streaming updates</li>
              <li>✓ Analytics hooks</li>
              <li>✓ A/B testing dashboard</li>
              <li>✓ Audit logs (90 days + export)</li>
              <li>✓ API access with roles</li>
            </ul>
            <button class="mt-6 w-full rounded-[6px] border border-white/70 py-2 text-[11px] font-semibold">Subscribe</button>
          </article>

          <article class="rounded-[8px] border border-[#D8DAE5] bg-white p-5">
            <div class="mb-2 flex items-center justify-between">
              <h3 class="text-[14px] font-semibold text-[#23265A]">Enterprise Plan</h3>
              <span class="rounded-full bg-[#ECECF6] px-2 py-0.5 text-[9px] font-semibold text-[#5E6075]">billed annually</span>
            </div>
            <p class="mb-4 text-[40px] font-bold leading-none text-[#23265A]">Custom</p>
            <ul class="space-y-2 text-[11px] text-[#4D4F64]">
              <li>✓ Unlimited API calls</li>
              <li>✓ Unlimited audit log retention</li>
              <li>✓ Full model access</li>
              <li>✓ Dedicated customer success manager</li>
              <li>✓ 24/7 support</li>
              <li>✓ Custom SLA (99.99% uptime)</li>
              <li>✓ VNet-based portal</li>
              <li>✓ Optional on-prem deployment</li>
            </ul>
            <button class="mt-6 w-full rounded-[6px] border border-[#BFC2D9] py-2 text-[11px] font-semibold text-[#24295C]">Subscribe</button>
          </article>
        </div>

        <div class="mt-5 text-center">
          <button class="rounded-[6px] border border-[#9CA0BF] px-4 py-2 text-[12px] font-semibold text-[#24295C]">View full price comparison</button>
        </div>

        <div class="mt-6 flex flex-col items-start justify-between gap-4 rounded-[8px] border border-[#D0D3E4] bg-[#FAFAFD] p-5 md:flex-row md:items-center">
          <div>
            <h3 class="text-[30px] font-semibold text-[#20254A]">Start your 7-days free Sandbox Plan</h3>
            <p class="text-[13px] text-[#72758B]">Join over 1,000+ startups already growing with Untitled.</p>
          </div>
          <div class="flex gap-3">
            <button class="rounded-[6px] bg-[#222754] px-5 py-2 text-[12px] font-semibold text-white">Get Started</button>
            <button class="rounded-[6px] border border-[#B7BCD8] px-5 py-2 text-[12px] font-semibold text-[#222754]">Learn More</button>
          </div>
        </div>
      </div>
    </section>

    <section class="px-4 pb-16 md:px-8 md:pb-20">
      <div class="mx-auto w-full max-w-[1240px] overflow-x-auto rounded-[8px] border border-[#BFC2D8] bg-white">
        <table class="min-w-[1024px] w-full border-collapse text-left text-[11px]">
          <thead>
            <tr class="bg-gradient-to-b from-[#3933A2] to-[#111330] text-white">
              <th class="border border-[#5E63A7] px-2 py-1.5">Features</th>
              <th class="border border-[#5E63A7] px-2 py-1.5">Standard</th>
              <th class="border border-[#5E63A7] px-2 py-1.5">Enhanced</th>
              <th class="border border-[#5E63A7] px-2 py-1.5">Enterprise</th>
            </tr>
          </thead>
          <tbody>
            <tr v-for="row in fullComparisonRows" :key="row.feature" class="odd:bg-white even:bg-[#F7F8FC]">
              <td class="border border-[#CFD2E4] px-2 py-1">{{ row.feature }}</td>
              <td class="border border-[#CFD2E4] px-2 py-1">{{ row.standard }}</td>
              <td class="border border-[#CFD2E4] px-2 py-1">{{ row.enhanced }}</td>
              <td class="border border-[#CFD2E4] px-2 py-1">{{ row.enterprise }}</td>
            </tr>
          </tbody>
          <tfoot>
            <tr class="bg-gradient-to-b from-[#3933A2] to-[#111330] text-white">
              <td class="border border-[#5E63A7] px-2 py-1.5 font-semibold">Price</td>
              <td class="border border-[#5E63A7] px-2 py-1.5 font-semibold">$10</td>
              <td class="border border-[#5E63A7] px-2 py-1.5 font-semibold">$149</td>
              <td class="border border-[#5E63A7] px-2 py-1.5 font-semibold">Custom</td>
            </tr>
          </tfoot>
        </table>
      </div>
    </section>
  </main>
</template>

<script setup>
const fullComparisonRows = [
  { feature: 'Core Feature Flags API', standard: '✓', enhanced: '✓', enterprise: '✓' },
  { feature: 'Targeting Rules Engine', standard: '✓ (basic)', enhanced: '✓ (advanced + custom attrs)', enterprise: '✓' },
  { feature: 'Percentage Rollouts', standard: '✓ (max 10 flags, 1 env)', enhanced: '✓ (unlimited flags, multi-env)', enterprise: '✓' },
  { feature: 'Kill Switch / Instant Rollback', standard: '✓', enhanced: '✓', enterprise: '✓' },
  { feature: 'Multi-Environment Support', standard: '✕', enhanced: '✓', enterprise: '✓' },
  { feature: 'Unlimited Flags & Projects', standard: '✕', enhanced: '✓', enterprise: '✓' },
  { feature: 'Environment-Specific Flags', standard: '✕', enhanced: '✓', enterprise: '✓' },
  { feature: 'Analytics Hooks (Flag Metrics)', standard: '✕', enhanced: '✓', enterprise: '✓' },
  { feature: 'A/B Testing Dashboard', standard: '✕', enhanced: '✓', enterprise: '✓' },
  { feature: 'Streaming Flag Updates (Real-Time)', standard: '✕', enhanced: '✓', enterprise: '✓' },
  { feature: 'SDK Caching & Offline Mode', standard: '✓', enhanced: '✓', enterprise: '✓' },
  { feature: 'Client Side SDKs', standard: '✓', enhanced: '✓', enterprise: '✓' },
  { feature: 'Dart Server SDK (OpenFeature)', standard: '✓', enhanced: '✓', enterprise: '✓' },
  { feature: 'Multi-Tenant Architecture', standard: '✕', enhanced: '✓', enterprise: '✓' },
  { feature: 'Audit Logs (Flag Changes)', standard: '✕', enhanced: '✓ (90 days + export)', enterprise: '✓ (unlimited + export)' },
  { feature: 'API Management Access', standard: '✕', enhanced: '✓ (multi-key + custom roles)', enterprise: '✓' },
  { feature: 'OpenFeature Compliance', standard: '✓', enhanced: '✓', enterprise: '✓' },
  { feature: 'SSO (SAML)', standard: '✕', enhanced: '✓', enterprise: '✓' },
  { feature: 'IP Allowlisting', standard: '✕', enhanced: '✕', enterprise: '✓' },
  { feature: 'Monthly API Calls', standard: '10k', enhanced: '100k (overage available)', enterprise: 'Unlimited (custom pricing)' },
  { feature: 'Log Retention', standard: '7 days', enhanced: '90 days', enterprise: 'Custom (1year+ if needed)' },
  { feature: 'Support SLA', standard: '72 hours', enhanced: '48 hours', enterprise: '24 hours' }
]
</script>
