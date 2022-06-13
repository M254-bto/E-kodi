<script>
import Sidebar from "../components/sidebar.svelte";
import Title from "../components/title.svelte";
import Dphoto from "../components/dphoto.svelte";
import Dash from "../components/dash.svelte";
import Search from "../components/search.svelte";
import Button from "../components/button.svelte";
import Row from "../components/row.svelte";


let text = [
    "Total Tenants", ""
]
</script>

<div class="container">
    <div class="side">
        <Sidebar/>
    </div>
    <div class="content">
        <div class="top">
            <div class="title"><Title/></div>
            <div class="dp"><Dphoto/></div>
        </div>
        <hr/>
        <div class="dashb">
            <Dash/>
            <Dash/>
            <Dash/>
        </div>
      
        <div class="search-row">
            <div class="search">
                <Search/>
                <Button/>
            </div>
            <div class="row">
                <Row/>
                <Row/>
                <Row/>
                <Row/>
                <Row/>
                <Row/>
                <Row/>
                <Row/>
                <Row/>
                <Row/>

                

            </div>
        </div>
    </div>
</div>

<style>
.container{
    margin: 0;
    width: 100vw;
    height: 100vh;
    overflow:hidden;
    display: grid;
    grid-template-columns: 23% 77%;
    
}

.side{
    height:100vh;
    left: 0;
}

.content{
    height: 100vh;
    overflow: hidden;
    background-color: #D2E0FB;
   

}
.top{
    margin: 20px 0 10px 0;
    width: 100%;
    height: 120px;
    display: grid;
    grid-template-columns: auto auto;
    
}
.title{
    margin: auto;
}
.dp{
    margin: auto;
}

.dashb{

    width: 90%;
    margin: auto;
    display: flex;
    flex-wrap: nowrap;
    justify-content: space-between;
   
}

.search-row{
    padding: 10px;
    width: 90%;
    margin: 30px auto;
    border: 2px solid #fff;
    border-radius: 24px;
    overflow-x: hidden;
    /* background-color: rgb(18, 29, 129); */
    
}
.search{
    display: grid;
    grid-template-columns:80% 15%;
    justify-content: space-between;
}
.row{
    width: 100%;
    margin: 15px auto;
    height: 300px;
    overflow-x: hidden;
   
}

</style>