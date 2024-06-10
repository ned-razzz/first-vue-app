<template>
  <section>
    <h2>My friends</h2>
    <ul>
      <li v-for="friend in friends">
        <h2>{{ friend.name }}</h2>
        <h2>{{ friend.email }}</h2>
      </li>
    </ul>
  </section>
</template>

<script>
export default {
  data() {
    return {
      friends: [
        {
          id: '1',
          name: 'Manuel Lorenz',
          phone: '01234 5678 991',
          email: 'manuel@localhost.com'
        },
        {
          id: '2',
          name: 'Julie Jones',
          phone: '09876 543 221',
          email: 'julie@localhost.com'
        }
      ]
    }
  }
}
</script>
