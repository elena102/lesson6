<template>
       <nav class="pagination">
                <ul class="pagination-list">
                    <li class="pagination-item">
                        <button class="pagination-transition">
                            <i class="fas fa-angle-left">
                            </i></button>
                    </li>
                    <li class="pagination-item">
                        <button class="pagination-link pagination-link--active">1</button>
                    </li>
                    <li class="pagination-item">
                        <button class="pagination-link">2</button>
                    </li>
                    <li class="pagination-item">
                        <button class="pagination-link">3</button>
                    </li>
                    <li class="pagination-item">
                        <button class="pagination-link">4</button>
                    </li>
                    <li class="pagination-item">
                        <button class="pagination-link">5</button>
                    </li>
                    <li class="pagination-item">
                        <button class="pagination-link">6</button>
                    </li>
                    <li class="pagination-item pagination-item--separator">
                        <span>....</span>
                    </li>
                    <li class="pagination-item">
                        <button class="pagination-link">20</button>
                    </li>
                    <li class="pagination-item">
                        <button class="pagination-transition">
                            <i class="fas fa-angle-right"></i></button>
                    </li>
                    
                </ul>
            </nav>
</template>

<script>
export default {
name:'Pagination'
}
</script>

<style>

</style>