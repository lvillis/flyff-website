<template>
  <div class="download">
    <div class="banner">
    </div>
    <div class="mainContent">
      <div class="container text-center">
        <h1>Get started playing <span class="color-red">Redux Flyff</span></h1>
        <p>
          Please make sure to follow all instructions below to make this installation process as<br>
          easy as possible! Skipping steps will lead you to errors and misconfiguration.
        </p>
      </div>
      <div class="container margin-top">
        <h1 class="m-0">
          <i class="fas fa-download"></i> Download
        </h1>
        <p class="mb-1">
          Please choose a method from the list below
        </p>
        <div class="border-div"></div>
      </div>
      <div class="container download-listings mt-md-4">
        <div class="row">
          <div class="col-md-3 download-col">
            <a href="/"></a>
            <i class="fas fa-box-open"></i>
            <h1>Installer</h1>
            <p>
              This installer will install and configure all pre-requisites for you.
            </p>
          </div>
          <div class="col-md-3 download-col">
            <a href="/"></a>
            <i class="fas fa-file-archive"></i>
            <h1>Client</h1>
            <p>
              <b class="color-red">NOTE:</b> You <b>must</b> install all pre-requisites for our client to work.
            </p>
          </div>
          <div class="col-md-3 download-col">
            <a href="/"></a>
            <i class="fas fa-clipboard-list"></i>
            <h1>Requirements</h1>
            <p>
              Zip package of ALL pre-requisites. Use if you already have client.
            </p>
          </div>
      </div>
      </div>

      <div class="container margin-top">
        <h1 class="m-0">
          <i class="fas fa-clipboard-check"></i> Instructions
        </h1>
        <p class="mb-1">
          Please follow this list carefully for proper install
        </p>
        <div class="border-div"></div>
      </div>
      <div class="container">
        <p><b>1.</b> Download the <a href="/">Installer</a> for Redux Flyff by clicking <a href="/">here</a></p>
        <p><b>2.</b> Whitelist the Redux Flyff install in your antivirus and then run as administrator. <a href="https://lmgtfy.com/?q=how+to+whitelist+an+application+in+my+antivirus" target="_blank">click here for how to whitelist</a></p>
        <p><b>3.</b> Locate the directory you installed Redux Flyff too and run ReduxFlyff.exe from the main folder, you may also need to allow this application through your anti-virus.</p>
      </div>


      <div class="container margin-top">
        <h1 class="m-0">
          <i class="fas fa-exclamation-triangle"></i> Troubleshooting
        </h1>
        <p class="mb-1">
          If you're having issues, please check if your issue is listed below.
        </p>
        <div class="border-div"></div>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-md-3 patch-col">
            <p>
              <b class="text-warning">Issue:</b> <br>My patcher is not patching
            </p>
            <p>
              <b class="text-success">Answer:</b><br>
              This issue is commonly caused by your anti-virus blocking connection to our patch server to download files. Please whitelist ReduxFlyff.exe in your anti-virus
            </p>
          </div>
          <div class="col-md-3 patch-col">
            <p>
              <b class="text-warning">Issue:</b> <br>My patching is showing Error: blahblah
            </p>
            <p>
              <b class="text-success">Answer:</b><br>
              This issue is commonly caused by missing pre-requisites. Please make sure to download all <a href="/">pre-requirements here</a> for our patcher to be able to work on your system.
            </p>
          </div>
          <div class="col-md-3 patch-col">
            <p>
              <b class="text-warning">Issue:</b> <br>My patcher is showeing Error: System.IO.IOExceptions
            </p>
            <p>
              <b class="text-success">Answer:</b><br>
              You may have installed Redux Flyff while your windows defender is on, This can often cause issues and will stop the installer from extracting important files for the client to work. Uninstall and reinstall with your defender switched off.

            </p>
          </div>
        </div>
      </div>




    </div>
  </div>
</template>


<style lang="scss" scoped>

.download-listings{



  .download-col {
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.1), 0 6px 20px 0 rgba(0, 0, 0, 0.1);
    padding: 2rem;
    border-radius: 8px;
    position: relative;
    text-align: center;
    margin: 0 1rem;

    &:first-child {
      margin-left: 0;
    }

    &:hover {
      box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.2);
      transition: 200ms ease-in-out;
      .fas {
        color: rgb(217, 43, 46);
        transition: 200ms ease-in-out;


      }
       h1 {
         color: rgb(217, 43, 46);
         transition: 200ms ease-in-out;

       }
    }

    a {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }
  }

  .fas {
    font-size: 3rem;
    margin-bottom: 0.8rem;
  }
}

  .patch-col {
    border: 1px solid rgba(0, 0, 0, 0.1);
    padding: 1rem;

    margin-left: 1rem;
  }

</style>