<template>
    <div>
        {{ route.params.id }}
        <svg width="590" height="373" viewBox="0 0 590 373" fill="none" xmlns="http://www.w3.org/2000/svg">
            <g id="14">
                <path id="14_2" d="M431 29.5H589.5V241.5H56.5V29.5H263.5H264V29V1H322.5H430.5V29V29.5H431Z"
                    fill="#134889" stroke="white" />
                <text id="Carrefour" fill="white" xml:space="preserve" style="white-space: pre"
                    font-family="Josefin Sans" font-size="40" letter-spacing="0em">
                    <tspan x="236.352" y="131">Carrefour</tspan>
                </text>
            </g>
        </svg>
    </div>
</template>

<script setup>
const route = useRoute();
</script>
