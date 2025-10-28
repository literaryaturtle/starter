<template>
  <div>
    <UPageHero
      title="Lumitone"
      description="A roblox utilly tool that allow you to manage your account remotely. Fast, stable and conveince."
      :links="[{
        label: 'Get started',
        to: 'https://dash.lumitone.xyz/',
        target: '_blank',
        trailingIcon: 'i-lucide-arrow-right',
        size: 'xl'
      }]"
    />

    <UPageSection
      id="features"
      title="How it works?"
      description="The way that we manage your accounts, devices"
      :features="[{
        icon: 'i-lucide-signal-high',
        title: 'Remote controlling',
        description: 'Lumitone allow you to manage your devices remotely from website.'
      }, {
        icon: 'i-lucide-calendar-check-2',
        title: 'Everything is scheduleable',
        description: 'With Lumitone, you can schedule any tasks in any time.'
      }, {
        icon: 'i-lucide-move-up-right',
        title: 'Instances rejoining',
        description: 'With our auto rejoin tool, your account will always active.'
      }]"
    />

    <UPageSection>
      <UPageCTA
        title="Ready to manage your accounts?"
        description="Join thousands of developers building with Nuxt and Nuxt UI. Get this template and start shipping today."
        variant="subtle"
        :links="[{
          label: 'Start building',
          to: 'https://ui.nuxt.com/docs/getting-started/installation/nuxt',
          target: '_blank',
          trailingIcon: 'i-lucide-arrow-right',
          color: 'neutral'
        }, {
          label: 'View on GitHub',
          to: 'https://github.com/nuxt-ui-templates/starter',
          target: '_blank',
          icon: 'i-simple-icons-github',
          color: 'neutral',
          variant: 'outline'
        }]"
      />
    </UPageSection>
  </div>
</template>
