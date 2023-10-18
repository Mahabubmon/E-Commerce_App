<template>
    

    <div class="container">
        <div class="row">
            <div class=" col-12 text-center">
                <h3 class="pt-3">Add category</h3>
            </div>
        </div>
        <div class="row">
            <div class="col-3"></div>
            <div class="col-6">
                <form>
                <div class="form-group">
                    <label for="">Name</label>
                    <input type="text" class="form-control" v-model ="categoryName">
                </div>
                <div class="form-group">
                    <label for="">Description</label>
                    <textarea type="text" class="form-control" v-model ="description"/>
                </div>
                <div class="form-group">
                    <label for="">Image</label>
                    <input type="text" class="form-control" v-model ="imageUrl">
                </div>
                <button type="submit" class="btn btn-primary" >Submit</button>
            </form>
            </div>
            <div class="col-3"></div>
            
        </div>
    </div>
</template>


<script>
export default{
    data(){
        return {
            categoryName:"",
            description:"",
            imageUrl:""
        }
    },

}

</script>