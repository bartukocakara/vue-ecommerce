<template>
      <table class="table">
        <thead>
            <tr>
                <th scope="col">Product</th>
                <th scope="col">Price</th>
                <th scope="col">Quantity</th>
                <th scope="col">Total</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>
                    <div class="media">
                        <div class="d-flex">
                            <img src="img/cart.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <p>Minimalistic shop for multipurpose use</p>
                        </div>
                    </div>
                </td>
                <td>
                    <h5>$360.00</h5>
                </td>
                <td>
                    <div class="product_count">
                        <input type="text" name="qty" id="sst" maxlength="12" value="1" title="Quantity:"
                            class="input-text qty">
                        <button onclick="var result = document.getElementById('sst'); var sst = result.value; if( !isNaN( sst )) result.value++;return false;"
                            class="increase items-count" type="button"><i class="lnr lnr-chevron-up"></i></button>
                        <button onclick="var result = document.getElementById('sst'); var sst = result.value; if( !isNaN( sst ) &amp;&amp; sst > 0 ) result.value--;return false;"
                            class="reduced items-count" type="button"><i class="lnr lnr-chevron-down"></i></button>
                    </div>
                </td>
                <td>
                    <h5>$720.00</h5>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="media">
                        <div class="d-flex">
                            <img src="img/cart.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <p>Minimalistic shop for multipurpose use</p>
                        </div>
                    </div>
                </td>
                <td>
                    <h5>$360.00</h5>
                </td>
                <td>
                    <div class="product_count">
                        <input type="text" name="qty" id="sst" maxlength="12" value="1" title="Quantity:"
                            class="input-text qty">
                        <button onclick="var result = document.getElementById('sst'); var sst = result.value; if( !isNaN( sst )) result.value++;return false;"
                            class="increase items-count" type="button"><i class="lnr lnr-chevron-up"></i></button>
                        <button onclick="var result = document.getElementById('sst'); var sst = result.value; if( !isNaN( sst ) &amp;&amp; sst > 0 ) result.value--;return false;"
                            class="reduced items-count" type="button"><i class="lnr lnr-chevron-down"></i></button>
                    </div>
                </td>
                <td>
                    <h5>$720.00</h5>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="media">
                        <div class="d-flex">
                            <img src="img/cart.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <p>Minimalistic shop for multipurpose use</p>
                        </div>
                    </div>
                </td>
                <td>
                    <h5>$360.00</h5>
                </td>
                <td>
                    <div class="product_count">
                        <input type="text" name="qty" id="sst" maxlength="12" value="1" title="Quantity:"
                            class="input-text qty">
                        <button onclick="var result = document.getElementById('sst'); var sst = result.value; if( !isNaN( sst )) result.value++;return false;"
                            class="increase items-count" type="button"><i class="lnr lnr-chevron-up"></i></button>
                        <button onclick="var result = document.getElementById('sst'); var sst = result.value; if( !isNaN( sst ) &amp;&amp; sst > 0 ) result.value--;return false;"
                            class="reduced items-count" type="button"><i class="lnr lnr-chevron-down"></i></button>
                    </div>
                </td>
                <td>
                    <h5>$720.00</h5>
                </td>
            </tr>
        </tbody>
    </table>
</template>

<script>

export default {
    name : "CustomerOrder"
}
</script>