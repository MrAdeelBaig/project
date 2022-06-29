<template>
    <div id="body">
        <Header></Header>
        <div id="u-update">
            <fieldset id="fieldset">
                <legend>Update User</legend>
                <title>Update User</title>
                <div id="register_form"><br />
                    <input type="text" id="name" name="name" placeholder="Enter your Name"
                        class="textfields"><br /><br />
                    <input type="text" id="username" name="username" placeholder="Enter your UserName"
                        class="textfields"><br /><br />
                    <input type="password" id="password" name="password" placeholder="Enter your password"
                        class="textfields"><br /><br />
                    <input type="text" id="address" name="address" placeholder="Enter your Address"
                        class="textfields"><br /><br />
                    <input type="text" id="city" name="city" placeholder="Enter your City"
                        class="textfields"><br /><br />
                    <input type="file" name="img" accept="image/x-png,image/gif,image/jpeg" /> <br /> <br />
                    <button type="submit" id="signup" class="button" v-on:click="Update">Update</button>
                </div>
            </fieldset>
        </div>
        <Footer></Footer>
    </div>
</template>
<script>
import Header from './Header.vue';
import Footer from './Footer.vue';
export default {
    name: "update-user",
    components: {
        Header,
        Footer,
    },
    methods:{
        Update(){
            alert('Insan ban');
        }
    }

}
</script>
