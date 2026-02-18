---
title: 重定向1
---
::: info
一个没啥用的通知
:::

::: tip
这是一个善意的提醒
:::

::: warning
在警告变为错误之前是没人关心的
:::

::: danger
这下你注意到了吧
:::

<script setup>
import { onMounted } from "vue"
import { useRouter } from "vitepress"
    
const router = useRouter();

onMounted(() => router.go("/"));
</script>
