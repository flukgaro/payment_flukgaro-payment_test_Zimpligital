<!-- Please remove this file from your project -->
<template>
  <div>
    <b-container >
      <b-row style="margin:20px 0px 20px 0px">
        <b-col md="7">
          <div class="delivery">
            <h4>
              Delivery
              <span style="color: green">
                <b-icon-check-circle></b-icon-check-circle
              ></span>
            </h4>
            <div style="font-weight: 500; font-size: 18px">
              Moblie Entry - Free
            </div>
            <div style="color: gray">Ticket Available by Sun Apr 3,2022</div>
            <div style="color: gray">
              These moblie tickets will be transferred directly to you from a
              trusted seller. We'll email you instructions on how to accept them
              on the original ticket provider's moblie app
            </div>
          </div>
          <div class="payment">
            <b-row>
              <b-col md="6"
                ><h4>
                  Payment
                  <span style="color: green">
                    <b-icon-check-circle></b-icon-check-circle
                  ></span></h4
              ></b-col>
              <b-col md="4" class="ml-auto"><div style="text-align:end;">logo someting</div></b-col>
            </b-row>

            <div style="margin: 20px; font-weight: 500; font-size: 18px">
              Use Credit / Debit Card
            </div>
            <div>
              <div class="visa-card">
                <b-row style="padding: 20px">
                  <b-col cols="1">
                    <div><b-form-radio size="lg" selected></b-form-radio></div>
                  </b-col>
                  <b-col cols="2">
                    <div> <img width="60px" height="60px" src="../assets/icons/Visa.png" /></div>
                  </b-col>
                  <b-col cols="9">
                    <div class="card_visa">Visa-9999</div>
                    <div>
                      <span class="username">User Name</span> |
                      <span class="exp">exp. 00/11</span>
                    </div>
                    <div>
                      <span class="edit">Edit</span> |
                      <span class="delete">Delete</span>
                    </div>
                  </b-col>
                </b-row>

                <div style="padding: 20px 0px 20px 60px">
                  <div>Security Code</div>
                  <b-row>
                    <b-col cols="3">
                      <div>
                        <b-form-input
                          id="input-valid"
                          type="password"
                          :state="true"
                          value="123"
                        ></b-form-input>
                      </div>
                    </b-col>
                    <b-col cols="8" style="margin: auto">
                      <div>
                        <span style="color: gray; margin-right: 20px"
                          ><b-icon-credit-card
                            scale="3"
                          ></b-icon-credit-card></span
                        ><span style="font-size: 14px"
                          >3-digits on back of card</span
                        >
                      </div>
                    </b-col>
                  </b-row>
                </div>
              </div>
              <div style="padding: 20px 40px 40px 40px">
                <span style="color: rgb(57, 87, 239); margin-right: 10px; cursor: pointer;"
                  ><b-icon-plus-lg scale="2"></b-icon-plus-lg
                ></span>
                <span style="margin-left: 30px; color: gray"
                  ><b-icon-credit-card2-front
                    scale="3"
                  ></b-icon-credit-card2-front
                ></span>
                <span
                  class="addnewcard"
                  style="
                    margin-left: 30px;
                    font-weight: 600;
                    font-size: 18px;
                    color: rgb(57, 87, 239);
                  "
                  >Add New Card</span
                >
              </div>

              <hr />
              <div class="orpaywith" style="font-weight: 600">
                <div style="font-size: 20px">Or Pay With</div>
                <div>
                  By using a digital wallet and continuing past this page, you
                  have read and are accepting the
                  <span class="terms"> Terms of Use</span>.
                </div>
              </div>
            </div>
          </div>
        </b-col>
        <b-col md="4" class="ml-5">
          <div class="total" >
            <div  style="
                  font-size: 1.5rem;
                  margin-bottom: 0.5rem;
                  font-weight: 500;
                  line-height: 1.2;
                ">
              <span
               
                >Total</span
              >
              <span class="money">$549.11 <b-icon-chevron-up style="color:gray"></b-icon-chevron-up></span>
            </div>
            <br />
            <div style="font-weight: 500; font-size: 18px">Tickets</div>
            <div >Resale Tickets: $229.00 x 2 <span style="float:right">$458.00</span></div>
            <br />
            <div style="font-weight: 500; font-size: 18px">Note From Seller</div>
            <div>
              xfr XFER Proof of at least one dose of COVID-19 vaccination of age
              5 to 11 and guests ages 12 and up will be required to show proof
              of two COVID-19 vaccine dose or one dose of the Johnson & Johnson
              vaccine Masks must be worn.
            </div>
            <br />
            <div style="font-weight: 500; font-size: 18px">Fees</div>
            <div>Service Fee: $44.08 x 2 <span style="float:right">$88.16</span></div>
            <div>Order Processing Fee <span style="float:right">$2.95</span></div>
            <br />
            <div style="font-weight: 500; font-size: 18px">Delivery</div>
            <div>Mobile Entry <span style="float:right">Free</span></div>
            <br />
            <div class="edit">Cancle Order</div>
            <br /><br />
            <div style="font-weight: 500; font-size: 16px">*All Sales Final-No Refunds</div>
            <div style="font-weight: 500; font-size: 14px">
              <b-form-checkbox
                >I have read and agree to the current
                <span class="terms">Terms of Use</span>.</b-form-checkbox
              >
            </div>
            <br />
            <b-button style="width:100%; height:45px" variant="success">Place Order</b-button>
            <br />
            <div style="font-weight: 500; font-size: 12px; margin:10px 0px 10px 0px">*Exceptions may apply,see our Terms of Use.</div>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "NuxtTutorial",  
  data() {
      return {
        selected: 'A',
        
      }}
  
};
</script>
<style scoped>
.delivery {
  border: 1px solid rgb(181, 181, 181);
  border-radius: 5px;
  margin-bottom: 20px;
  padding: 20px;
}
.payment {
  border: 1px solid rgb(181, 181, 181);
  border-radius: 5px;
  margin-bottom: 20px;
  padding: 20px;
}
.total {
  border: 1px solid rgb(181, 181, 181);
  border-radius: 5px;
  margin-bottom: 20px;
  padding: 20px;
}
.visa-card {
  border: 1px solid rgb(198, 216, 251);
  background-color: rgba(198, 227, 251, 0.717);
  margin: 15px;
  border-radius: 5px;
}
.card_visa {
  font-weight: 500;
  font-size: 18px;
}
.username {
  font-size: 18px;
  color: gray;
}
.exp{
  font-size: 18px;
  color: gray;
}
.edit {
  font-weight: 500;
  color: rgb(57, 87, 239);
  cursor: pointer;
}
.delete {
  font-weight: 500;
  color: rgb(57, 87, 239);
  cursor: pointer;
}
.terms {
  color: rgb(78, 78, 238);
  cursor: pointer;
}
.money{
  float: right;
  margin: auto;
}
.hover{
  cursor: pointer;
}
</style>
