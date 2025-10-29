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
        description="Join today."
        variant="subtle"
        :links="[{
          label: 'Join now',
          to: 'https://dash.lumitone.xyz',
          target: '_blank',
          trailingIcon: 'i-lucide-arrow-right',
          color: 'neutral'
        }]"
      />
    </UPageSection>
  </div>
</template>
