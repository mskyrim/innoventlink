<template>
    <div class="overflow-auto rounded-lg shadow hidden md:block">
      <span class="self-center text-xl font-semibold sm:text-2xl whitespace-nowrap dark:text-white">All Incidents</span>
      <table class="w-full">
        <thead class="bg-gray-50 border-b-2 border-gray-200">
        <tr>
          <th class="w-20 p-3 text-sm font-semibold tracking-wide text-left">No.</th>
          <th class="p-3 text-sm font-semibold tracking-wide text-left">Details</th>
          <th class="w-24 p-3 text-sm font-semibold tracking-wide text-left">Severity</th>
         
          <th class="w-24 p-3 text-sm font-semibold tracking-wide text-left">Created at</th>
          <th class="w-32 p-3 text-sm font-semibold tracking-wide text-left">Status</th>
          <th class="w-28 p-3 text-sm font-semibold tracking-wide text-left">Alert source</th>
          <th class="w-28 p-3 text-sm font-semibold tracking-wide text-left">Service</th>
        </tr>
        </thead>
        <tbody class="divide-y divide-gray-100">
        <tr class="bg-white">
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
            <a href="#" class="font-bold text-blue-500 hover:underline">10001</a>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
            Kring New Fit office  mesh + PU, black
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
          <span
            class="p-1.5 text-xs font-medium uppercase tracking-wider text-red-800 bg-red-200 rounded-lg bg-opacity-50">Critical</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">20 hours ago</td>
          <td class="p-3 text-sm text-gray-700  whitespace-nowrap ">
            <span
            class="p-1.5 text-xs font-medium text-green-700  tracking-wider  bg-green-200 rounded-lg bg-opacity-50">Open</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Email</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Backend Service</td>
        </tr>
        <tr class="bg-gray-50">
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
            <a href="#" class="font-bold text-blue-500 hover:underline">10002</a>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Kring New Fit office + PU, black</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
          <span
            class="p-1.5 text-xs font-medium uppercase tracking-wider text-yellow-800 bg-yellow-200 rounded-lg bg-opacity-50">Major</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">4 hours ago</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
          <span
            class="p-1.5 text-xs font-medium text-green-700  tracking-wider  bg-green-200 rounded-lg bg-opacity-50">Open</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Jira Cloud</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Backend Service</td>
        </tr>
        <tr class="bg-white">
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
            <a href="#" class="font-bold text-blue-500 hover:underline">10003</a>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Kring New Fit office  + PU, black</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
          <span
            class="p-1.5 text-xs font-medium uppercase tracking-wider text-gray-800 bg-gray-200 rounded-lg bg-opacity-50">Minor</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">a day ago</td>
          <td class="p-3 text-sm   text-green-800     ">
            <span
            class="p-1.5 text-xs font-medium text-blue-700  tracking-wider  bg-blue-200 rounded-lg bg-opacity-50">Closed</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Jira Cloud</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">API Monitoring</td>
        </tr>
        <tr class="bg-gray-50">
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
            <a href="#" class="font-bold text-blue-500 hover:underline">10003</a>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Kring New Fit office  + PU, black</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
          <span
            class="p-1.5 text-xs font-medium uppercase tracking-wider text-gray-800 bg-gray-200 rounded-lg bg-opacity-50">Minor</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">a day ago</td>
          <td class="p-3 text-sm   text-green-800     ">
            <span
            class="p-1.5 text-xs font-medium text-blue-700  tracking-wider  bg-blue-200 rounded-lg bg-opacity-50">Closed</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Jira Cloud</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">API Monitoring</td>
        </tr>
        <tr class="bg-white">
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
            <a href="#" class="font-bold text-blue-500 hover:underline">10003</a>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Kring New Fit office  + PU, black</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
          <span
            class="p-1.5 text-xs font-medium uppercase tracking-wider text-gray-800 bg-gray-200 rounded-lg bg-opacity-50">Minor</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">a day ago</td>
          <td class="p-3 text-sm   text-green-800     ">
            <span
            class="p-1.5 text-xs font-medium text-blue-700  tracking-wider  bg-blue-200 rounded-lg bg-opacity-50">Closed</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Jira Cloud</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">API Monitoring</td>
        </tr>
        <tr class="bg-gray-50">
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
            <a href="#" class="font-bold text-blue-500 hover:underline">10003</a>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Kring New Fit office  + PU, black</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
          <span
            class="p-1.5 text-xs font-medium uppercase tracking-wider text-gray-800 bg-gray-200 rounded-lg bg-opacity-50">Minor</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">a day ago</td>
          <td class="p-3 text-sm   text-green-800     ">
            <span
            class="p-1.5 text-xs font-medium text-blue-700  tracking-wider  bg-blue-200 rounded-lg bg-opacity-50">Closed</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Jira Cloud</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">API Monitoring</td>
        </tr>
        <tr class="bg-white">
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
            <a href="#" class="font-bold text-blue-500 hover:underline">10003</a>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Kring New Fit office  + PU, black</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
          <span
            class="p-1.5 text-xs font-medium uppercase tracking-wider text-gray-800 bg-gray-200 rounded-lg bg-opacity-50">Minor</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">a day ago</td>
          <td class="p-3 text-sm   text-green-800     ">
            <span
            class="p-1.5 text-xs font-medium text-blue-700  tracking-wider  bg-blue-200 rounded-lg bg-opacity-50">Closed</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Jira Cloud</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">API Monitoring</td>
        </tr>
        <tr class="bg-gray-50">
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
            <a href="#" class="font-bold text-blue-500 hover:underline">10003</a>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Kring New Fit office  + PU, black</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
          <span
            class="p-1.5 text-xs font-medium uppercase tracking-wider text-gray-800 bg-gray-200 rounded-lg bg-opacity-50">Minor</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">a day ago</td>
          <td class="p-3 text-sm   text-green-800     ">
            <span
            class="p-1.5 text-xs font-medium text-blue-700  tracking-wider  bg-blue-200 rounded-lg bg-opacity-50">Closed</span>
          </td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Jira Cloud</td>
          <td class="p-3 text-sm text-gray-700 whitespace-nowrap">API Monitoring</td>
        </tr>
        
        </tbody>
      </table>
    </div>
</template>