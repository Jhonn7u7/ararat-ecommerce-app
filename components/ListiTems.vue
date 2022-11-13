<template> <!-- ESTRUCTURA DEL CARITO -->
<div class="flex flex-col w-full flex-nowrap lg:flex-row mt-6">
  <div class="grid h-auto flex-grow card  rounded-box place-items-center">
    <div class="overflow-x-auto w-full">
  <table class="table w-full lg:m-6">
    <!-- head -->
    <thead>
      <tr>
        <th>
          <label>
            <input type="checkbox" class="checkbox" />
          </label>
        </th>
        <th>Articulo</th>
        <th>Precio</th>
        <th>Cantidad</th>
        <th></th>
      </tr>
    </thead>
    <tbody>
      <!-- row 1 -->
      <tr>
        <th>
          <label>
            <input type="checkbox" class="checkbox" />
          </label>
        </th>
        <td>
          <div class="flex items-center space-x-3">
            <div class="avatar">
              <div class="mask mask-squircle w-16 h-16">
                <img src="images/camisa.webp" alt="Product" />
              </div>
            </div>
            <div>
              <div class="font-bold">Playera Polo</div>
              <div class="text-sm opacity-50">Negro</div>
            </div>
          </div>
        </td>
        <td>
          <h2 class="font-bold">$250</h2>
        </td>
        <td>
            <h2 class="font-bold">2</h2>
        </td>
      </tr>
    </tbody>
  </table>
    </div>
  </div>
  <div class="grid h-auto flex-grow place-items-center">
    <div class="card w-96 bg-base-100 shadow-xl">
      <div class="card-body">
        <h2 class="card-title">Resumen del pedido!</h2>
        <p>Subtotal: <span class="font-black text-2xl">$MXN259.00</span></p>
        <div class="card-actions">
        <button class="btn hover:bg-red-200 bg-red-300 outline-none m-2">Pagar Ahora</button>
        </div>
     </div>
    </div>
  </div>
</div>
</template>