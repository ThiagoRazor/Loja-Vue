<template>
    <div class="bg-white relative lg:py-20">
        <div
            class="flex flex-col items-center justify-center pt-0 pr-10 pb-0 pl-10 mt-0 mr-auto mb-0 ml-auto max-w-7xl
                                                                                                            xl:px-5 lg:flex-row">
            <div class="flex flex-col items-center justify-center w-full pt-5 pr-10 pb-20 pl-10 lg:pt-20 lg:flex-row">
                <div class="w-full mt-20 mr-0 mb-0 ml-0 relative z-10 max-w-2xl lg:mt-0 lg:w-5/12">
                    <div
                        class="flex flex-col items-start justify-start pt-10 pr-10 pb-10 pl-10 bg-white shadow-2xl rounded-xl
                                                                                                                    relative z-10">
                        <p class="w-full text-4xl font-medium text-center leading-snug font-serif">Cadastre-se na plataforma
                        </p>
                        <div class="w-full mt-6 mr-0 mb-0 ml-0 relative space-y-8">
                            <div class="relative">
                                <p
                                    class="bg-white pt-0 pr-2 pb-0 pl-2 -mt-3 mr-0 mb-0 ml-2 font-medium text-gray-600 absolute">
                                    Usuário
                                </p>
                                <input placeholder="John" type="text" class="border placeholder-gray-400 focus:outline-none
                                                    focus:border-black w-full pt-4 pr-4 pb-4 pl-4 mt-2 mr-0 mb-0 ml-0 text-base block bg-white
                                                    border-gray-300 rounded-md" />
                            </div>
                            <div class="relative">
                                <p
                                    class="bg-white pt-0 pr-2 pb-0 pl-2 -mt-3 mr-0 mb-0 ml-2 font-medium text-gray-600 absolute">
                                    Email</p>
                                <input placeholder="123@ex.com" type="text" class="border placeholder-gray-400 focus:outline-none
                                                focus:border-black w-full pt-4 pr-4 pb-4 pl-4 mt-2 mr-0 mb-0 ml-0 text-base block bg-white
                                                border-gray-300 rounded-md" />
                            </div>
                            <div class="relative">
                                <p
                                    class="bg-white pt-0 pr-2 pb-0 pl-2 -mt-3 mr-0 mb-0 ml-2 font-medium text-gray-600 absolute">
                                    Senha
                                </p>
                                <input placeholder="Password" type="password" class="border placeholder-gray-400 focus:outline-none
                                                focus:border-black w-full pt-4 pr-4 pb-4 pl-4 mt-2 mr-0 mb-0 ml-0 text-base block bg-white
                                                border-gray-300 rounded-md" />
                            </div>
                            <div class="relative">
                                <a class="w-full inline-block pt-4 pr-5 pb-4 pl-5 text-xl font-medium text-center text-white bg-indigo-500
                                                rounded-lg transition duration-200 hover:bg-indigo-600 ease">Confirmar</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>