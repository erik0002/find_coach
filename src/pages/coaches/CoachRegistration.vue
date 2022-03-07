<template>
  <section>
    <base-card>
      <h2>Register as a coach now!</h2>
      <coach-form></coach-form>
    </base-card>
  </section>
</template>


<script>
import CoachForm from '@/components/coaches/CoachForm';
import BaseCard from '@/components/ui/BaseCard';

export default {
    components: {
      BaseCard,
      CoachForm
    }
}
</script>
