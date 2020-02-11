<template>
    <div class="card">
        <div class="card-header">
            <h1 class="card-title">{{ patchTitle }}</h1>
        </div>
        <div class="card-body">
            <p class="card-text">{{ patchDesc}}</p>
        </div>
        <div class="card-footer text-muted">
            Post Date: {{ patchDate}}
        </div>
    </div>

</template>
<script>
  import '../assets/main.scss'

export default {
  name: 'patchnotes',
  props: {
    patchTitle: String,
    patchDate: Date,
    patchDesc: String
  }
}
</script>

<style lang="scss" scoped>
.card {
    margin: 2rem 0;

     &:first-child {
         margin-top: 0;   
    }
    .card-header {
        background: none;
        h1 {
            margin: 0;
        }
    }
    .card-body {
        .card-title {
            h1 {
                margin: 0;
            }
        }
        .card-text, p {
            color: #858585;
        }
    }
    .card-footer {
        font-size: 12px;
    }
}
</style>