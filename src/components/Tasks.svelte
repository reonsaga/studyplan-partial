<!--Overall Parent Container-->
<div class="flex-1 flex justify-center items-center xl:ml-64">
    <div class="p-4 w-full">
        <div class="mb-4 w-full">
            <div class="flex items-center justify-center rounded w-full">
                <div class="relative min-h-screen z-10 w-full">
                    <div
                        class="top-4 left-3 flex flex-col items-center space-y-4 w-full"
                    >
                        <!--Searchbar Container-->
                        <div
                            class="pt-4 px-4 pb-4 bg-white border xl:w-4/6 lg:w-5/6 md:w-5/6 w-full border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700 space-y-4"
                        >
                            <form class="max-w-lg mx-auto">
                                <div class="flex">
                                    <label
                                        for="search-dropdown"
                                        class="mb-2 text-sm font-medium text-gray-900 sr-only dark:text-white"
                                        >Your Email</label
                                    >
                                    <button
                                        id="dropdown-button"
                                        data-dropdown-toggle="dropdown"
                                        class="flex-shrink-0 z-10 inline-flex items-center py-2.5 px-4 text-sm font-medium text-center text-gray-900 bg-gray-100 border border-gray-300 rounded-s-lg hover:bg-gray-200 focus:ring-4 focus:outline-none focus:ring-gray-100 dark:bg-gray-700 dark:hover:bg-gray-600 dark:focus:ring-gray-700 dark:text-white dark:border-gray-600"
                                        type="button"
                                        >All categories <svg
                                            class="w-2.5 h-2.5 ms-2.5"
                                            aria-hidden="true"
                                            xmlns="http://www.w3.org/2000/svg"
                                            fill="none"
                                            viewBox="0 0 10 6"
                                        >
                                            <path
                                                stroke="currentColor"
                                                stroke-linecap="round"
                                                stroke-linejoin="round"
                                                stroke-width="2"
                                                d="m1 1 4 4 4-4"
                                            />
                                        </svg></button
                                    >
                                    <div
                                        id="dropdown"
                                        class="z-10 hidden bg-white divide-y divide-gray-100 rounded-lg shadow w-44 dark:bg-gray-700"
                                    >
                                        <ul
                                            class="py-2 text-sm text-gray-700 dark:text-gray-200"
                                            aria-labelledby="dropdown-button"
                                        >
                                            <li>
                                                <button
                                                    type="button"
                                                    class="inline-flex w-full px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"
                                                    >School</button
                                                >
                                            </li>
                                            <li>
                                                <button
                                                    type="button"
                                                    class="inline-flex w-full px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"
                                                    >Work</button
                                                >
                                            </li>
                                            <li>
                                                <button
                                                    type="button"
                                                    class="inline-flex w-full px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"
                                                    >Games</button
                                                >
                                            </li>
                                            <li>
                                                <button
                                                    type="button"
                                                    class="inline-flex w-full px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"
                                                    >Exercise</button
                                                >
                                            </li>
                                        </ul>
                                    </div>
                                    <div class="relative w-full">
                                        <input
                                            type="search"
                                            id="search-dropdown"
                                            class="block p-2.5 w-full z-20 text-sm text-gray-900 bg-gray-50 rounded-e-lg border-s-gray-50 border-s-2 border border-gray-300 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-s-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:border-blue-500"
                                            placeholder="Search tasks..."
                                            required
                                        />
                                        <button
                                            type="submit"
                                            class="absolute top-0 end-0 p-2.5 text-sm font-medium h-full text-white bg-pink-500 rounded-e-lg border border-pink-500 hover:bg-pink-700 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
                                        >
                                            <svg
                                                class="w-4 h-4"
                                                aria-hidden="true"
                                                xmlns="http://www.w3.org/2000/svg"
                                                fill="none"
                                                viewBox="0 0 20 20"
                                            >
                                                <path
                                                    stroke="currentColor"
                                                    stroke-linecap="round"
                                                    stroke-linejoin="round"
                                                    stroke-width="2"
                                                    d="m19 19-4-4m0-7A7 7 0 1 1 1 8a7 7 0 0 1 14 0Z"
                                                />
                                            </svg>
                                            <span class="sr-only">Search</span>
                                        </button>
                                    </div>
                                    <div class="flex mx-4">
                                        <button
                                            data-modal-target="authentication-modal"
                                            data-modal-toggle="authentication-modal"
                                            type="button"
                                            class="text-pink-500 border border-pink-500 bg-white hover:bg-pink-500 hover:text-white hover font-bold rounded-full text-sm p-2.5 text-center inline-flex items-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
                                        >
                                            <svg
                                                xmlns="http://www.w3.org/2000/svg"
                                                fill="none"
                                                viewBox="0 0 24 24"
                                                stroke-width="1.5"
                                                stroke="currentColor"
                                                class="size-5"
                                            >
                                                <path
                                                    stroke-linecap="round"
                                                    stroke-linejoin="round"
                                                    d="M12 4.5v15m7.5-7.5h-15"
                                                />
                                            </svg>

                                            <span class="sr-only">Add task</span
                                            >
                                        </button>
                                    </div>
                                </div>
                            </form>
                        </div>

                        <!--Tasks Card Container 2-->
                        <div
                            class="pt-4 px-4 pb-4 mb-4 bg-white border xl:w-4/6 lg:w-5/6 md:w-5/6 w-full max-w-full border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700 space-y-4"
                        >
                            <div class="flex flex-col mb-4">
                                <!--Date-->
                                <div
                                    class="flex flex-row justify-between items-center"
                                >
                                    <h1 class="font-bold mb-1 text-lg">
                                        October 1, 2024
                                    </h1>
                                    <div class="hidden md:flex space-x-6">
                                        <!--Tasks Parameters Heading-->
                                        <h1
                                            class="text-md text-lg text-right w-24 md:w-20 lg:w-20"
                                        >
                                            Status
                                        </h1>

                                        <h1
                                            class="text-md text-lg text-right w-24 md:w-20 lg:w-20"
                                        >
                                            Priority
                                        </h1>

                                        <h1
                                            class="text-md text-lg text-right w-24 md:w-20 lg:w-20"
                                        >
                                            Category
                                        </h1>

                                        <h1
                                            class="text-md text-lg text-right w-24 md:w-20 lg:w-20"
                                        >
                                            Deadline
                                        </h1>
                                    </div>
                                </div>

                                <hr class="bg-gray-500" />

                                <!-- Task Section -->
                                <div
                                    class="flex flex-row items-center justify-between mt-4 mb-4"
                                >
                                    <div class="flex items-center">
                                        <input
                                            id="default-checkbox"
                                            type="checkbox"
                                            value=""
                                            class="w-5 h-5 text-pink-500 bg-gray-100 border-gray-300 rounded focus:ring-pink-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
                                        />
                                        <!--Task Name(button leads to readonly Task Details)-->
                                        <button
                                            data-modal-target="readonly-modal"
                                            data-modal-toggle="readonly-modal"
                                            type="button"
                                            class="text-gray-500 hover:text-pink-500 rounded-lg text-sm text-center ms-4 dark:border-blue-500 dark:text-blue-500 dark:hover:text-white dark:hover:bg-blue-500 dark:focus:ring-blue-800"
                                            >Task 1</button
                                        >
                                    </div>

                                    <!--Task Parameter Values-->
                                    <div
                                        class="hidden md:flex space-x-6 flex-grow justify-end"
                                    >
                                        <span
                                            class="text-yellow-300 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >In Progress</span
                                        >

                                        <span
                                            class="text-red-500 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >High</span
                                        >

                                        <span
                                            class="text-gray-900 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >School</span
                                        >

                                        <span
                                            class="text-pink-500 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >4 hr left</span
                                        >
                                    </div>
                                </div>
                                <hr class="bg-gray-500" />
                                <div
                                    class="flex flex-row items-center justify-between mt-4"
                                >
                                    <div class="flex items-center">
                                        <input
                                            id="default-checkbox"
                                            type="checkbox"
                                            value=""
                                            class="w-5 h-5 text-pink-500 bg-gray-100 border-gray-300 rounded focus:ring-pink-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
                                        />
                                        <!--Task Name(button leads to readonly Task Details)-->
                                        <button
                                            data-modal-target="readonly-modal"
                                            data-modal-toggle="readonly-modal"
                                            type="button"
                                            class="text-gray-500 hover:text-pink-500 rounded-lg text-sm text-center ms-4 dark:border-blue-500 dark:text-blue-500 dark:hover:text-white dark:hover:bg-blue-500 dark:focus:ring-blue-800"
                                            >Task 1</button
                                        >
                                    </div>

                                    <!--Task Parameter Values-->
                                    <div
                                        class="hidden md:flex space-x-6 flex-grow justify-end"
                                    >
                                        <span
                                            class="text-yellow-300 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >In Progress</span
                                        >

                                        <span
                                            class="text-red-500 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >High</span
                                        >

                                        <span
                                            class="text-gray-900 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >School</span
                                        >

                                        <span
                                            class="text-pink-500 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >4 hr left</span
                                        >
                                    </div>
                                </div>
                            </div>
                            <hr class="bg-gray-500" />
                        </div>

                        <!--Tasks Card Container-->
                        <div
                            class="pt-4 px-4 pb-4 mb-4 bg-white border xl:w-4/6 lg:w-5/6 md:w-5/6 w-full max-w-full border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700 space-y-4"
                        >
                            <div class="flex flex-col mb-4">
                                <!--Date-->
                                <div
                                    class="flex flex-row justify-between items-center"
                                >
                                    <h1 class="font-bold mb-1 text-lg">
                                        October 2, 2024
                                    </h1>
                                    <div class="hidden md:flex space-x-6">
                                        <!--Tasks Parameters Heading-->
                                        <h1
                                            class="text-md text-lg text-right w-24 md:w-20 lg:w-20"
                                        >
                                            Status
                                        </h1>

                                        <h1
                                            class="text-md text-lg text-right w-24 md:w-20 lg:w-20"
                                        >
                                            Priority
                                        </h1>

                                        <h1
                                            class="text-md text-lg text-right w-24 md:w-20 lg:w-20"
                                        >
                                            Category
                                        </h1>

                                        <h1
                                            class="text-md text-lg text-right w-24 md:w-20 lg:w-20"
                                        >
                                            Deadline
                                        </h1>
                                    </div>
                                </div>

                                <hr class="bg-gray-500" />

                                <!-- Task Section -->
                                <div
                                    class="flex flex-row items-center justify-between mt-4 mb-4"
                                >
                                    <div class="flex items-center">
                                        <input
                                            id="default-checkbox"
                                            type="checkbox"
                                            value=""
                                            class="w-5 h-5 text-pink-500 bg-gray-100 border-gray-300 rounded focus:ring-pink-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
                                        />
                                        <!--Task Name(button leads to readonly Task Details)-->
                                        <button
                                            data-modal-target="readonly-modal"
                                            data-modal-toggle="readonly-modal"
                                            type="button"
                                            class="text-gray-500 hover:text-pink-500 rounded-lg text-sm text-center ms-4 dark:border-blue-500 dark:text-blue-500 dark:hover:text-white dark:hover:bg-blue-500 dark:focus:ring-blue-800"
                                            >Task 1</button
                                        >
                                    </div>

                                    <!--Task Parameter Values-->
                                    <div
                                        class="hidden md:flex space-x-6 flex-grow justify-end"
                                    >
                                        <span
                                            class="text-yellow-300 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >In Progress</span
                                        >

                                        <span
                                            class="text-red-500 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >High</span
                                        >

                                        <span
                                            class="text-gray-900 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >School</span
                                        >

                                        <span
                                            class="text-pink-500 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >4 hr left</span
                                        >
                                    </div>
                                </div>
                                <hr class="bg-gray-500" />
                                <div
                                    class="flex flex-row items-center justify-between mt-4"
                                >
                                    <div class="flex items-center">
                                        <input
                                            id="default-checkbox"
                                            type="checkbox"
                                            value=""
                                            class="w-5 h-5 text-pink-500 bg-gray-100 border-gray-300 rounded focus:ring-pink-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
                                        />
                                        <!--Task Name(button leads to readonly Task Details)-->
                                        <button
                                            data-modal-target="readonly-modal"
                                            data-modal-toggle="readonly-modal"
                                            type="button"
                                            class="text-gray-500 hover:text-pink-500 rounded-lg text-sm text-center ms-4 dark:border-blue-500 dark:text-blue-500 dark:hover:text-white dark:hover:bg-blue-500 dark:focus:ring-blue-800"
                                            >Task 1</button
                                        >
                                    </div>

                                    <!--Task Parameter Values-->
                                    <div
                                        class="hidden md:flex space-x-6 flex-grow justify-end"
                                    >
                                        <span
                                            class="text-yellow-300 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >In Progress</span
                                        >

                                        <span
                                            class="text-red-500 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >High</span
                                        >

                                        <span
                                            class="text-gray-900 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >School</span
                                        >

                                        <span
                                            class="text-pink-500 font-bold text-sm w-24 md:w-20 lg:w-20 text-center"
                                            >4 hr left</span
                                        >
                                    </div>
                                </div>
                            </div>
                            <hr class="bg-gray-500" />
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<!--Add task pop-up-->
<div
    id="authentication-modal"
    tabindex="-1"
    aria-hidden="true"
    class="hidden overflow-y-auto overflow-x-hidden fixed inset-0 z-50 flex justify-center items-center"
>
    <div class="relative w-full max-w-md md:max-w-lg lg:max-w-xl p-4">
        <!-- Modal content -->
        <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
            <!-- Modal header -->
            <div
                class="flex items-center justify-between p-4 md:p-5 border-b rounded-t dark:border-gray-600"
            >
                <h3 class="text-xl font-semibold text-gray-900 dark:text-white">
                    Create task
                </h3>
                <button
                    type="button"
                    class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm w-8 h-8 inline-flex justify-center items-center dark:hover:bg-gray-600 dark:hover:text-white"
                    data-modal-hide="authentication-modal"
                >
                    <svg
                        class="w-3 h-3"
                        aria-hidden="true"
                        xmlns="http://www.w3.org/2000/svg"
                        fill="none"
                        viewBox="0 0 14 14"
                    >
                        <path
                            stroke="currentColor"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="m1 1 6 6m0 0 6 6M7 7l6-6M7 7l-6 6"
                        />
                    </svg>
                    <span class="sr-only">Close modal</span>
                </button>
            </div>

            <!-- Modal body -->
            <div class="p-4 md:p-5">
                <form class="space-y-4" action="#">
                    <div>
                        <label
                            for="taskname"
                            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                            >Task name</label
                        >
                        <input
                            type="taskname"
                            name="taskname"
                            id="taskname"
                            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
                            placeholder="Task name..."
                            required
                        />
                    </div>

                    <label
                        aria-label="disabled input 2"
                        for="taskdetails"
                        class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                        >Task details</label
                    >
                    <textarea
                        id="taskdetails"
                        rows="4"
                        class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus:ring-pink-500 focus:border-pink-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                        placeholder="Task details..."
                    ></textarea>

                    <label
                        for="taskprio"
                        class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                        >Priority</label
                    >
                    <ul
                        class="items-center w-full text-sm font-medium text-gray-900 bg-white border border-gray-200 rounded-lg sm:flex dark:bg-gray-700 dark:border-gray-600 dark:text-white"
                    >
                        <li
                            class="w-full border-b border-gray-200 sm:border-b-0 sm:border-r dark:border-gray-600"
                        >
                            <div class="flex items-center ps-3">
                                <input
                                    id="horizontal-list-radio-license"
                                    type="radio"
                                    value=""
                                    name="list-radio"
                                    class="w-4 h-4 text-red-500 bg-gray-100 border-gray-300 focus:ring-pink-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 dark:focus:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500"
                                />
                                <label
                                    for="horizontal-list-radio-license"
                                    class="w-full py-3 ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                                    >High
                                </label>
                            </div>
                        </li>
                        <li
                            class="w-full border-b border-gray-200 sm:border-b-0 sm:border-r dark:border-gray-600"
                        >
                            <div class="flex items-center ps-3">
                                <input
                                    id="horizontal-list-radio-military"
                                    type="radio"
                                    value=""
                                    name="list-radio"
                                    class="w-4 h-4 text-yellow-300 bg-gray-100 border-gray-300 focus:ring-pink-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 dark:focus:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500"
                                />
                                <label
                                    for="horizontal-list-radio-military"
                                    class="w-full py-3 ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                                    >Normal</label
                                >
                            </div>
                        </li>
                        <li class="w-full dark:border-gray-600">
                            <div class="flex items-center ps-3">
                                <input
                                    id="horizontal-list-radio-passport"
                                    type="radio"
                                    value=""
                                    name="list-radio"
                                    class="w-4 h-4 text-green-500 bg-gray-100 border-gray-300 focus:ring-pink-500 dark:focus:ring-pink-600 dark:ring-offset-gray-700 dark:focus:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500"
                                />
                                <label
                                    for="horizontal-list-radio-passport"
                                    class="w-full py-3 ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                                    >Low</label
                                >
                            </div>
                        </li>
                    </ul>

                    <div class="grid grid-cols-2 gap-4">
                        <div class="col-span-2 sm:col-span-1">
                            <label
                                for="category"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                            >
                                Category
                            </label>
                            <select
                                id="category"
                                placeholder="Select category..."
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-pink-500 focus:border-pink-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                            >
                                <option value="TV">School</option>
                                <option value="PC">Work</option>
                                <option value="GA">Games</option>
                                <option value="PH">Exercise</option>
                            </select>
                        </div>

                        <div class="relative col-span-2 sm:col-span-1">
                            <label
                                for="deadline"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                            >
                                Deadline
                            </label>
                            <input
                                datepicker
                                id="default-datepicker"
                                datepicker-orientation="top right"
                                type="text"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-pink-500 focus:border-pink-500 block w-full pl-10 pr-10 py-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                placeholder="Select date..."
                            />
                        </div>
                    </div>

                    <button
                        type="submit"
                        class="w-full text-white border border-pink-500 bg-pink-500 hover:bg-white hover:text-pink-500 hover:bg-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
                    >
                        Submit Task
                    </button>
                </form>
            </div>
        </div>
    </div>
</div>

<!--Readonly tasks (when clicking a certain task)-->
<div
    id="readonly-modal"
    tabindex="-2"
    aria-hidden="true"
    class="hidden overflow-y-auto overflow-x-hidden fixed inset-0 z-50 flex justify-center items-center"
>
    <div class="relative w-full max-w-md md:max-w-lg lg:max-w-xl p-4">
        <!-- Modal content -->
        <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
            <!-- Modal header -->
            <div
                class="flex items-center justify-between p-4 md:p-5 border-b rounded-t dark:border-gray-600"
            >
                <h3 class="text-xl font-semibold text-gray-900 dark:text-white">
                    View Task
                </h3>
                <button
                    type="button"
                    class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm w-8 h-8 inline-flex justify-center items-center dark:hover:bg-gray-600 dark:hover:text-white"
                    data-modal-hide="readonly-modal"
                >
                    <svg
                        class="w-3 h-3"
                        aria-hidden="true"
                        xmlns="http://www.w3.org/2000/svg"
                        fill="none"
                        viewBox="0 0 14 14"
                    >
                        <path
                            stroke="currentColor"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="m1 1 6 6m0 0 6 6M7 7l6-6M7 7l-6 6"
                        />
                    </svg>
                    <span class="sr-only">Close modal</span>
                </button>
            </div>

            <!-- Modal body -->
            <div class="p-4 md:p-5">
                <form class="space-y-4" action="#">
                    <div>
                        <input
                            type="taskname"
                            name="taskname"
                            id="taskname"
                            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
                            placeholder="Task name..."
                            required
                            disabled
                            readonly
                        />
                    </div>

                    <textarea
                        id="taskdetails"
                        rows="4"
                        class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus:ring-pink-500 focus:border-pink-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                        placeholder="Task details..."
                        disabled
                        readonly
                    ></textarea>

                    <label
                        for="taskprio"
                        class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                        >Priority</label
                    >
                    <ul
                        class="items-center w-full text-sm font-medium text-gray-900 bg-white border border-gray-200 rounded-lg sm:flex dark:bg-gray-700 dark:border-gray-600 dark:text-white"
                    >
                        <li
                            class="w-full border-b border-gray-200 sm:border-b-0 sm:border-r dark:border-gray-600"
                        >
                            <div class="flex items-center ps-3">
                                <input
                                    checked
                                    id="horizontal-list-radio-license"
                                    type="radio"
                                    value=""
                                    name="list-radio"
                                    class="w-4 h-4 text-red-500 bg-gray-100 border-gray-300 focus:ring-pink-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 dark:focus:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500"
                                    disabled
                                />
                                <label
                                    for="horizontal-list-radio-license"
                                    class="w-full py-3 ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                                    >High
                                </label>
                            </div>
                        </li>
                        <li
                            class="w-full border-b border-gray-200 sm:border-b-0 sm:border-r dark:border-gray-600"
                        >
                            <div class="flex items-center ps-3">
                                <input
                                    id="horizontal-list-radio-military"
                                    type="radio"
                                    value=""
                                    name="list-radio"
                                    class="w-4 h-4 text-yellow-300 bg-gray-100 border-gray-300 focus:ring-pink-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 dark:focus:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500"
                                    disabled
                                />
                                <label
                                    for="horizontal-list-radio-military"
                                    class="w-full py-3 ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                                    >Normal</label
                                >
                            </div>
                        </li>
                        <li class="w-full dark:border-gray-600">
                            <div class="flex items-center ps-3">
                                <input
                                    id="horizontal-list-radio-passport"
                                    type="radio"
                                    value=""
                                    name="list-radio"
                                    class="w-4 h-4 text-green-500 bg-gray-100 border-gray-300 focus:ring-pink-500 dark:focus:ring-pink-600 dark:ring-offset-gray-700 dark:focus:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500"
                                    disabled
                                />
                                <label
                                    for="horizontal-list-radio-passport"
                                    class="w-full py-3 ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                                    >Low</label
                                >
                            </div>
                        </li>
                    </ul>

                    <div class="grid grid-cols-2 gap-4">
                        <div class="col-span-2 sm:col-span-1">
                            <label
                                for="category"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                            >
                                Category
                            </label>
                            <select
                                id="category"
                                placeholder="Select category..."
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-pink-500 focus:border-pink-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                disabled
                            >
                                <option value="TV">School</option>
                                <option value="PC">Work</option>
                                <option value="GA">Games</option>
                                <option value="PH">Exercise</option>
                            </select>
                        </div>

                        <div class="relative col-span-2 sm:col-span-1">
                            <label
                                for="deadline"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                            >
                                Deadline
                            </label>
                            <input
                                datepicker
                                id="default-datepicker"
                                datepicker-orientation="top right"
                                type="text"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-pink-500 focus:border-pink-500 block w-full pl-10 pr-10 py-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                placeholder="Select date..."
                                disabled
                                readonly
                            />
                        </div>
                    </div>
                    <label
                        for="taskprio"
                        class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                        >Task Status</label
                    >
                    <ul
                        class="items-center w-full text-sm font-medium text-gray-900 bg-white border border-gray-200 rounded-lg sm:flex dark:bg-gray-700 dark:border-gray-600 dark:text-white"
                    >
                        <li
                            class="w-full border-b border-gray-200 sm:border-b-0 sm:border-r dark:border-gray-600"
                        >
                            <div class="flex items-center ps-3">
                                <input
                                    id="horizontal-list-radio-license"
                                    type="radio"
                                    value=""
                                    name="list-radio"
                                    class="w-4 h-4 text-green-500 bg-gray-100 border-gray-300 focus:ring-pink-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 dark:focus:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500"
                                />
                                <label
                                    for="horizontal-list-radio-license"
                                    class="w-full py-3 ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                                    >Completed
                                </label>
                            </div>
                        </li>
                        <li
                            class="w-full border-b border-gray-200 sm:border-b-0 sm:border-r dark:border-gray-600"
                        >
                            <div class="flex items-center ps-3">
                                <input
                                    checked
                                    id="horizontal-list-radio-military"
                                    type="radio"
                                    value=""
                                    name="list-radio"
                                    class="w-4 h-4 text-yellow-300 bg-gray-100 border-gray-300 focus:ring-pink-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 dark:focus:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500"
                                />
                                <label
                                    for="horizontal-list-radio-military"
                                    class="w-full py-3 ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                                    >In Progress</label
                                >
                            </div>
                        </li>
                    </ul>
                    <div class="grid grid-cols-2 gap-4">
                        <div class="flex justify-center">
                            <button
                                type="submit"
                                class="w-5/6 text-white border border-pink-500 bg-pink-500 hover:bg-white hover:text-pink-500 hover:bg-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
                            >
                                Finish
                            </button>
                        </div>
                        <div class="flex justify-center">
                            <button
                                type="submit"
                                class="w-5/6 text-white border border-red-500 bg-red-500 hover:bg-white hover:text-red-700 hover:border-red-700 hover:bg-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
                            >
                                Delete Task
                            </button>
                        </div>
                    </div>
                </form>
            </div>
        </div>
    </div>
</div>
