<template>
<div class="content-wrapper pl-3 pr-3 pb-3 pt-3 mb-2" style="height: inherit; width:inherit;">
    <!-- Content Header (Page header) -->
    <section class="content-header">
        <div class="container-fluid">
          <div class="row mb-2">
            <div class="col-sm-6">
              <h1>{{ $route.meta.title }}</h1>
            </div>
            <div class="col-sm-6">
              <ol class="breadcrumb float-sm-right">
                <li class="breadcrumb-item"><a href="/home">Home</a></li>
                <li class="breadcrumb-item active">{{ $route.meta.title }}</li>
              </ol>
            </div>
          </div>
        </div><!-- /.container-fluid -->
      </section>

    <!-- Main content -->
    <section class="content">


        <div class="row justify-content-center">
            <div class="col-md-12">
                <div class="card">
                    <div class="card-header">{{ $route.meta.title }}</div>

                   <div class="card-body">

                        <h2>A vision board of sorts</h2>
                        <br>
                        Something to help you visualize your vision upon completion of each goal.
                        <br>
                        <h3>Coming Soon...</h3>
                    </div>
                </div>
            </div>
        </div>


    </section>
    <!-- /.content -->


    <!-- Banner for Greydesk by greymore. DO NOT REMOVE UNDER ANY CIRCUMSTANCES -->
    <br>
    <br>
    <br>
    <br>
    <br>
    <div class="row justify-content-center center-block">
        <div class="col-md-10 justify-content-center center-block">
        <img src="img/greydeskbanner.svg">
        </div>
    </div>
    <br>
    <br>
    <!-- END of Banner for Greydesk by greymore. DO NOT REMOVE UNDER ANY CIRCUMSTANCES -->


</div>
  <!-- /.content-wrapper -->


</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
