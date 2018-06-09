<template>
	<nav class="panel column is-offset-2 is-8">
        <p class="panel-heading">
            Vuejs Phonebook
        </p>
        <div class="panel-block">
            <button class="button is-link is-outlined is-pulled-right">
                Add New
            </button>
        </div>
            
        <div class="panel-block">
            <p class="control has-icons-left">
                <input class="input is-small" type="text" placeholder="search">
                <span class="icon is-small is-left">
                    <i class="fas fa-search" aria-hidden="true"></i>
                </span>
            </p>
        </div>
        <a class="panel-block">
            <span class="column is-9">
            	Pavel Parvej
            </span>
            <span class="has-text-danger panel-icon column is-1">
                <i class="fas fa-trash-alt" aria-hidden="true"></i>
            </span>
            <span class="has-text-info panel-icon column is-1">
                <i class="fas fa-edit" aria-hidden="true"></i>
            </span>
            <span class="has-text-primary panel-icon column is-1">
                <i class="fas fa-eye" aria-hidden="true"></i>
            </span>
        </a>
</nav>
</template>