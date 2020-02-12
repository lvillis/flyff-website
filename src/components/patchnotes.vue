<template>
    <div class="card">
        <div class="card-header text-right">

            <div class="badge badge-hotfix">{{ patchFlagTitle}}</div>

        </div>
        <div class="card-body">
            <h1 class="card-title">{{ patchTitle }}</h1>
            <p class="card-text">{{ patchDesc}}</p>
        </div>
        <div class="card-footer text-muted">
            <div class="row">
                <div class="col-8">
                    Post Date: {{ patchDate}}
                </div>
                <div class="col-4 text-right color-red read-more">
                    <a href="/">Read More <i class="fas fa-caret-right pl-1"></i></a>
                </div>
            </div>

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
    patchDesc: String,
    patchFlagTitle: String,
    patchFlagColor: String
  }
}
</script>

<style lang="scss" scoped>
.card {
    margin: 2rem 0;
    border-radius: 8px;

     &:first-child {
         margin-top: 0;   
    }
    .card-header {
        background-image: url("../assets/images/patchnote_banner.jpg");
        height: 200px;
        background-position: center;

        .badge {
            box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
            padding: 0.40rem 1.4rem;

        }

        .badge-hotfix {
            background-color: rgb(217,43, 46);
            color: white;
        }
    }

    .card-body {
      

        img {
            margin-bottom: 1rem;
            width: 100%;
        }

        h1 {
            font-size: 23px;
        }
        .card-text, p {
            color: #858585;
        }
    }
    .card-footer {
        font-size: 12px;

        .read-more {
            a {
                color: rgb(217,43, 46);
            }

            .fas {
                font-size: 0.8rem;
            }
        }
    }
}
</style>