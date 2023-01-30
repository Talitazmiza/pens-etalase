<template>
    
    <div class="flex flex-row bg-blue-500">
        <div class="basis-9/12">
            <!-- searchbar -->
            <input type="text" placeholder="Ketik Judul" class="input input-bordered input-sm w-full max-w-lg bg-white" />
        </div>
        <div>
            <!-- advance search button -->
            <!-- The button to open modal -->
            <label for="my-modal-4" class="btn btn-sm btn-outline">Advance Search</label>
            
            <!-- Put this part before </body> tag -->
            <input type="checkbox" id="my-modal-4" class="modal-toggle" />
            <label for="my-modal-4" class="modal cursor-pointer">
                <label class="modal-box relative bg-black" for="">
                    <h3 class="text-lg font-bold text-center">Advance Search</h3>
                    <div class="flex flex-col text-black gap-5">
                        <div class="bg-green-200">
                            <input type="text" placeholder="Judul" class="input input-bordered w-full max-w-xs bg-white" />
                        </div>
                        <div class="bg-red-200">
                            <select class="select select-bordered w-full max-w-xs bg-white">
                                <option disabled selected>Tema</option>
                                <option>Education</option>
                                <option>Ehealth</option>
                                <option>Ecommerce</option>
                            </select>
                        </div>
                        <div class="bg-blue-200">
                            <select class="select select-bordered w-full max-w-xs bg-white">
                                <option disabled selected>Teknologi yang digunakan</option>
                                <option>ReactJS</option>
                                <option>VueJS</option>
                                <option>NodeJS ExpressJS</option>
                                <option>Laravel</option>
                                <option>None of the list</option>
                            </select>
                        </div>
                        <div class="bg-lime-200">
                            <select class="select select-bordered w-full max-w-xs bg-white">
                                <option disabled selected>Metode</option>
                                <option>Microservices</option>
                                <option>Cloud Platform</option>
                                <option>Microservices</option>
                                <option>Cloud Platform</option>
                                <option>None of the list</option>
                            </select>
                        </div>
                        <button class="btn btn-info btn-sm">Cari</button>
                    </div>
                </label>
            </label>
        </div>
    </div>
</template>
