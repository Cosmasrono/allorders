<template>
  <main class="min-h-screen bg-slate-800">
    <div class="flex flex-col justify-center items-center p-2 pt-10 mx-auto max-w-md rounded bg-slate-900">
        <Form @submit="onSubmit" class="flex flex-col gap-y-3 justify-center items-center p-3 mx-auto">
            <h4 class="py-2 w-full font-mono text-center text-white uppercase rounded bg-slate-700">Register with Us</h4>
            <Field name="text" placeholder="enter your name" class="px-14 py-3 rounded focus:ring-1 focus:ring-blue-600" required/>
            <Field name="email" type="email" placeholder="enter your email" class="px-14 py-3 rounded focus:ring-1 focus:ring-blue-600" :rules="validateEmail"/>
            <input type="submit" class="flex justify-self-center items-center px-8 py-2 bg-blue-600 rounded" value="Register"/>
        </Form>
    </div>
  </main>
</template>

<script>
import { Form, Field } from 'vee-validate';

export default {
  components: {
    Form,
    Field,
  },
  methods: {
    onSubmit(values) {
      console.log(JSON.stringify(values, null,2));
    },
    validateEmail(value){
        if(!value){
            return 'this field is required'
        }
        const regex =  /^[A-Z0-9._%+-]+@[A-Z0-9.-]+\.[A-Z]{2,4}$/i;
        if(!regex.test(value)){
            return ("input a valid email")
        }
        return true

        
    },
},
};
</script>

<style>

</style>