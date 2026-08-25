<!-- <script setup>
import {ref} from 'vue'

const name = ref('');
const age = ref('')
const address = ref('');
const course = ref('');
const year = ref('');
const fName= ref('');
const lName = ref(''); 
const mI = ref('');
const eMail = ref('');
const birtdate = ref('');
const sh = ref('');
</script>
    <template>
     <h1>Form</h1>
    <form @submit.prevent="submition">
        <input v-model= "fname" type ="text" placeholder="Enter your name"><br><br>
        <input v-model= "mi" type ="text" placeholder="Enter your MiddleName"><br><br>
        <input v-model= "lName" type ="type" placeholder="Enter your LastName"><br><br>
        <input v-model= "eMail" type ="type" placeholder="Email"><br><br>
        <input v-model= "birtdate" type ="text" placeholder="Birtdate"><br><br>
        <input v-model= "age" type ="number" placeholder="Enter your Age"><br><br>
        <input v-model= "address" type ="text" placeholder="Enter your address"><br><br>
        <input v-model= "course" type ="text" placeholder="Course"><br><br>
        <input v-model= "year" type ="number" placeholder="Year"><br><br>
        <input v-model= "sh" type ="type" placeholder="Description"><br><br>
                            <button>Submit</button>
        <h3>FirstName:{{ fname }}</h3>
        <h3>Middlename:{{ mi }}</h3>
        <h3>LastName:{{ lName }}</h3>
        <h3>Email:{{ eMail }}</h3>
        <h3>Birtdate:{{ birtdate }}</h3>
        <h3>Age:{{ age }}</h3>
        <h3>Address:{{address}}</h3>
        <h3>Course:{{ course}}</h3>
        <h3>Year:{{ year }}</h3>
        <h3>Description:{{ sh }}</h3>
        <h2></h2>
</form>

</template> -->