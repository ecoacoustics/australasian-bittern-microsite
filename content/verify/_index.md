+++
title = "Can you hear an Australasian Bittern?"
+++

<oe-verification-grid data-campaign="Australasian Bittern" id="verification-grid" grid-size="1" progress-bar-position="top">
    <template>
        <div class="tile-spacing">
            <oe-subject-tag></oe-subject-tag>
            <oe-media-controls for="spectrogram"></oe-media-controls>
        </div>
        <oe-axes>
        <oe-indicator>
            <oe-spectrogram id="spectrogram" mel-scale></oe-spectrogram>
        </oe-indicator>
        </oe-axes>
        <div class="tile-block">
            <oe-task-meter></oe-task-meter>
        </div>
    </template>
    <oe-verification verified="true" shortcut="y">Yes</oe-verification>
    <oe-verification verified="false" shortcut="n">No</oe-verification>
    <oe-verification verified="unsure" shortcut="u">Unsure</oe-verification>
</oe-verification-grid>

<style>
    body {
        background-color: var(--micro-background-dark);
    }
</style>
