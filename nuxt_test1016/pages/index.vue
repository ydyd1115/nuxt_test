<template>
  <div class="container">
    <table>
      <tr>
      <th>生徒一覧</th>|<th>管理者</th>
      </tr>
      <tr>
      <td><NuxtLink :to="{path:'/students'}" >生徒の情報を見る</NuxtLink></td>|
      <td><NuxtLink :to="{path:'/management'}">管理画面を見る</NuxtLink></td>
      </tr>
    </table>
  </div>
</template>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

tr{
  border:solid 1px black
}
</style>