<template>
    <div class="max-w-5xl mx-auto flex flex-col min-h-svh px-4 py-8 gap-8">
        <header class="flex flex-col gap-1">
            <h1 class="text-3xl font-bold tracking-tight">
                Custom Registry
            </h1>
            <p class="text-muted-foreground">
                A custom registry for distributing code using shadcn-vue.
            </p>
        </header>

        <main class="flex flex-col flex-1 gap-8">
            <div class="flex flex-col gap-4 border rounded-lg p-4 min-h-[450px] relative">
                <div class="flex items-center justify-between">
                    <h2 class="text-sm text-muted-foreground sm:pl-3">
                        A simple hello world component
                    </h2>
                </div>
                <div class="flex items-center justify-center min-h-[400px] relative">
                    <HelloWorld />
                </div>
            </div>
            <div class="flex flex-col gap-4 border rounded-lg p-4 min-h-[450px] relative">
                <div class="flex items-center justify-between">
                    <h2 class="text-sm text-muted-foreground sm:pl-3">
                        A simple use card example
                    </h2>
                </div>
                <div class="flex items-center justify-center min-h-[400px] relative">
                    <UseCard />
                </div>
            </div>
        </main>
    </div>
</template>

<script lang="ts" setup>
import { HelloWorld } from '@/registry/blocks/hello-world'
import { UseCard } from '~/registry/example/use-card'
</script>
