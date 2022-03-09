<template>
  <TheInnerPageHead title="Contact us" />
  <section class="why_section layout_padding">
    <div class="container">
      <div class="row">
        <div class="col-lg-8 offset-lg-2">
          <div class="full">
            <form action="index.html">
              <fieldset>
                <input
                  type="text"
                  placeholder="Enter your full name"
                  name="name"
                  required
                />
                <input
                  type="email"
                  placeholder="Enter your email address"
                  name="email"
                  required
                />
                <input
                  type="text"
                  placeholder="Enter subject"
                  name="subject"
                  required
                />
                <textarea placeholder="Enter your message" required></textarea>
                <input type="submit" value="Submit" />
              </fieldset>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>
  <TheArrival />
  <TheFooter />
</template>
<script>
import TheInnerPageHead from "@/components/TheInnerPageHead.vue";
import TheArrival from "@/components/TheArrival.vue";
import TheFooter from "@/components/TheFooter.vue";
export default {
  components: {
    TheInnerPageHead,
    TheArrival,
    TheFooter,
  },
};
</script>
<style scoped>
.layout_padding {
  padding: 70px 0;
}
.why_section .box {
    text-align: center;
    margin-top: 45px;
    background-color: #002c3e;
    padding: 45px 50px;
    border-radius: 5px;
    color: #ffffff;
}
.why_section .box .img-box {
  margin-bottom: 15px;
}

.why_section .box .img-box svg {
  width: 55px;
  height: auto;
  fill: #ffffff;
}
div.form_sub .field input[type="email"], div.form_sub .field input[type="email"]:hover, div.form_sub .field input[type="email"]:focus {
    padding: 10px 110px 10px 15px;
    border-radius: 0;
    border: solid #ccc 1px;
    font-size: 14px;
    position: relative;
    box-shadow: none;
    width: 100%;
    height: 48px;
}

.form_sub {
    position: relative;
}

.form_sub input[type="email"] + input[type="submit"] {
    position: absolute;
    right: 0;
    background: #f7444e;
    color: #fff;
    border: none;
    top: 0px;
    font-size: 14px;
    height: 48px;
    font-weight: 600;
    padding: 0 15px;
}

form input {
    background: #fff;
    border: solid #ccc 1px;
    padding: 15px 15px;
    width: 100%;
    font-size: 14px;
    margin-bottom: 20px;
    text-transform: capitalize;
    line-height: normal;
}

form textarea {
    background: #fff;
    border: solid #ccc 1px;
    padding: 15px 15px;
    width: 100%;
    min-height: 150px;
    font-size: 14px;
    margin-bottom: 20px;
    text-transform: capitalize;
    line-height: normal;
}

form input[type="submit"] {
    border: none;
    padding: 15px 45px;
    width: auto;
    font-size: 16px;
    text-transform: capitalize;
    line-height: normal;
    margin: 0 auto;
    display: flex;
    background: #333;
    color: #fff;
    font-weight: 600;
    transition: ease all 0.1s;
}

form input[type="submit"]:hover,
form input[type="submit"]:focus {
    background: #f7444e;
    color: #fff;
}
</style>
