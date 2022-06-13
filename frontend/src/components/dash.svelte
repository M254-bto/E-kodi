<script>
export let text;

</script>


<div class="main">
<div class="txt"><p class="p">Pending Payment</p></div>
<div class="num"><p class="np">488</p></div>
</div>



<style>
.main{
    width: 287px;
    height: 100px;
    background: #B7BED3;
    border-radius: 38px;
    display: flex;
    flex-direction: column;
}
.txt, .num{
    width: 90%;
    margin: auto;
    align-items: center;
    text-align: center;
    padding:0;
}
.p, .np{
    font-family: 'Inter';
    font-style: normal;
    font-weight: 700;
    font-size: 24px;
    line-height: 29px;
    margin: 0;
    /* identical to box height */


    color: #0C407A;
}
.np{
    font-size: 35px !important;
}

</style>
