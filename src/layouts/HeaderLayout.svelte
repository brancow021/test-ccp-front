<div class="flex justify-between px-4 items-center border h-28 headerCustom">
    <div class="flex justify-center w-6/12">
        <img 
            width="172" 
            height="39" 
            src={sourceCuembyImg} 
            alt="Cuemby"
        >
    </div>

    <div class="h-full flex items-center justify-center w-full">
        <ul class="flex w-full h-full">
            <li class="h-full flex w-full justify-center items-center mx-10 monserratFont text-cuemby-blue font-semibold">
                Company
            </li>
            <li class="h-full flex active border-b-2 w-full justify-center items-center mx-10 monserratFont text-cuemby-blue font-semibold">
                Our Results
            </li>
            <li class="h-full flex w-full justify-center items-center mx-10 monserratFont text-cuemby-blue font-semibold">
                Services
            </li>
            <li class="h-full flex w-full justify-center items-center mx-10 monserratFont text-cuemby-blue font-semibold">
                The Cause
            </li>
            <li class="h-full flex w-full justify-center items-center mx-10 monserratFont text-cuemby-blue font-semibold">
                Blog
            </li>
        </ul>
    </div>

    <div class="flex justify-end items-center w-6/12">
        <div class="mx-7">
            <button class="bg-blue-higlight p-2 rounded-xl w-40">
                <p class="monserratFont text-white text-lg">
                    Book a demo
                </p>
            </button>
        </div>

        <div class="mx-4">
            <img 
                height="18" 
                width="18" 
                src={SearchIcon} 
                alt="Search Icon"
            >
        </div>
        <div>
            <img height="26" src={Bar} alt="Bar">
        </div>
        <div class="mx-4">
            <img 
                height="37" 
                width="36" 
                src={UnitedStates} 
                alt="Search Icon"
            >
        </div>
    </div>
</div>


<script>
  export const sourceCuembyImg = "images/Cuemby.svg"
  export const SearchIcon = "images/SearchIcon.svg"
  export const UnitedStates = "images/UnitedStates.svg"
  export const Bar = "images/bar.svg"


</script>


<style>
    .active {
        border-color: #3C44EA;
    }
</style>


