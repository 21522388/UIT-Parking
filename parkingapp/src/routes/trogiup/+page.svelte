<script lang='ts'>
    import { Accordion, AccordionItem } from '@skeletonlabs/skeleton';
</script>

<div class="flex flex-1 md:2/3 xl:w-1/2 mx-auto my-16 justify-center bg-black/10 rounded">
    <Accordion autocollapse>
        <AccordionItem>
            <svelte:fragment slot="summary">
                <p class="font-bold">Câu hỏi 1?</p>
            </svelte:fragment>
            <svelte:fragment slot="content">
                Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
            </svelte:fragment>
        </AccordionItem>
        <AccordionItem>
            <svelte:fragment slot="summary">
                <p class="font-bold">Câu hỏi 2?</p>
            </svelte:fragment>
            <svelte:fragment slot="content">
                Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
            </svelte:fragment>
        </AccordionItem>
        <AccordionItem>
            <svelte:fragment slot="summary">
                <p class="font-bold">Câu hỏi 3?</p>
            </svelte:fragment>
            <svelte:fragment slot="content">
                Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
            </svelte:fragment>
        </AccordionItem>
        <AccordionItem>
            <svelte:fragment slot="summary">
                <p class="font-bold">Câu hỏi 4?</p>
            </svelte:fragment>
            <svelte:fragment slot="content">
                Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
                <br>Trả lời cho câu hỏi
            </svelte:fragment>
        </AccordionItem>
    </Accordion>
</div>
