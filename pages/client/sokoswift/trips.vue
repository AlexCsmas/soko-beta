<template>
  <div>
    <div class="flex mx-auto px-20">
      <div class="flex flex-col">
        <NavRoutes />
        <div>
          
            <h1 class="my-3 text-xl">Trip Reports</h1>

           <dataTables/>

          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
import NavRoutes from "~/components/NavRoutes/swift";
import dataTables from "~/components/dataTables/Swift/trips";
export default {
  components: {
    NavRoutes,
    dataTables,
  },
};
</script>

   

